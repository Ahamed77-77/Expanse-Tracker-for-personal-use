# Copilot Instructions for Expense Tracker

## Project Overview
This is a simple personal expense tracker web app. The main UI is defined in `index.html`. The project currently consists of static HTML and references a `style.css` for styling (not present in the workspace yet).

## Key Files
- `index.html`: Main application UI. Contains containers for balance, income, expenses, transaction list, and a form for adding transactions.
- `README.md`: Project title only; no additional documentation.

## Architecture & Data Flow
- All logic is expected to be client-side (JavaScript), but no JS files are present yet.
- Transactions are displayed in the `#transaction-list` element.
- Balance, income, and expenses are updated in their respective elements (`#Balance`, `#income-amount`, `#expenses-amount`).
- The form for adding transactions should be implemented inside the `#transaction-form` element.

## Developer Workflows
- No build tools, package managers, or test frameworks are present.
- Development is direct HTML/CSS/JS editing; open `index.html` in a browser to view changes.
- No backend or external API integration is currently set up.

## Project-Specific Patterns
- Use semantic HTML for UI structure.
- All state and logic should be managed in-browser (localStorage recommended for persistence).
- Keep UI updates in sync with data changes (e.g., updating balance after adding a transaction).

## Recommendations for AI Agents
- When adding features, keep all logic client-side unless a backend is introduced.
- If adding JavaScript, create a new file (e.g., `script.js`) and link it in `index.html`.
- If implementing persistence, use browser storage (localStorage).
- Follow the existing UI structure and update DOM elements by ID as needed.
- Document any new conventions or workflows in this file for future agents.

## Example: Adding a Transaction
- Add a form to `#transaction-form` for inputting transaction name and amount.
- On submit, update the transaction list and recalculate balance/income/expenses.
- Store transactions in localStorage for persistence.

---
Update this file as the project evolves, especially when adding new files, workflows, or conventions.