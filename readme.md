# Online Banking User Stories

## User Story 1: Checking Account Balance

**As a** bank customer,  
**I want to** be able to check my account balance online,  
**So that** I can easily monitor my funds.

### Acceptance Criteria:
- The user sees the current balance of all accounts on the dashboard after logging in.
- The user can select a specific account to view its current balance and latest transactions.
- The user is prompted to log in if not logged in or if the session expires when trying to access account balance.

## User Story 2: Transferring Funds Between Accounts

**As a** bank customer,  
**I want to** transfer funds between my accounts online,  
**So that** I can manage my finances conveniently.

### Acceptance Criteria:
- The user can select accounts for both the source and destination of the transfer.
- The transfer amount entered by the user cannot exceed the available balance in the source account.
- The user receives a confirmation message after a successful transfer.
- The user is notified if the transfer fails due to insufficient funds or other errors.
- The transfer reflects immediately in the account balances of both the source and destination accounts.

## User Story 3: Scheduling Future and Recurring Payments

**As a** bank customer,  
**I want to** schedule future and recurring payments from my account,  
**So that** I can manage regular expenses automatically.

### Acceptance Criteria:
- The user can set up a payment with a future date.
- The user can configure a recurring payment with specified frequency (e.g., weekly, monthly).
- The scheduled payment must not exceed the available account balance at the time of the transaction.
- The user receives a confirmation message after successfully scheduling a payment.
- The user is notified of upcoming payments at least one day before the scheduled date.
- The user can view, modify, or cancel any scheduled payments.
- Recurring payments continue until a specified end date or until manually cancelled by the user.
