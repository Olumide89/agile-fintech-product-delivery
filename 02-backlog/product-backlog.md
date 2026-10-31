# Prioritized Product Backlog

**Simulation scenario** | Prioritized using business value, risk, dependency and effort

| Rank | Epic | User story | Acceptance criteria | Estimate | Priority |
|---|---|---|---|---:|---|
| 1 | Account setup | As a new user, I want to create a secure account so that my financial data is protected. | User can register with email and password; password rules enforced; account verified; unauthorized access prevented. | 5 | Must have |
| 2 | Transactions | As a user, I want to import bank transactions so that I can see my spending in one place. | User can upload CSV; transactions appear in a list; duplicates are flagged; import errors are clearly reported. | 8 | Must have |
| 3 | Transactions | As a user, I want transactions automatically categorized so that I can understand my spending. | System suggests a category; user can accept or change it; category is saved for future imports. | 8 | Must have |
| 4 | Budgeting | As a user, I want to set a monthly budget for each category so that I can control spending. | User can create, edit and delete category budgets; total budget is calculated; budgets are saved. | 5 | Must have |
| 5 | Insight | As a user, I want to see spending against each budget so that I know whether I am on track. | Dashboard shows budget, spent, remaining and percentage used; data refreshes after each import. | 8 | Must have |
| 6 | Alerts | As a user, I want an alert when I approach my budget limit so that I can adjust my spending. | Alert is triggered at 80% and 100%; user can choose email or in-app notification; duplicate alerts are prevented. | 5 | Should have |
| 7 | Compliance | As a customer, I want my financial data handled according to applicable privacy requirements so that my information remains protected. | Data access is role-controlled; personal data is encrypted; consent and deletion requests are supported; audit trail is available. | 8 | Must have |
| 8 | Reporting | As a user, I want to view monthly spending trends so that I can identify changes in my behaviour. | User can view current and previous three months; trends are shown by category; data is accurate after import. | 5 | Should have |
| 9 | Performance | As a user, I want the dashboard to load quickly so that I can review my budget without delay. | Dashboard loads within three seconds for a standard user dataset; performance test passes. | 5 | Should have |
| 10 | Support | As a user, I want clear error messages so that I know what to do when an import fails. | Errors identify the affected file and row; guidance is provided; support can trace the error. | 3 | Could have |
