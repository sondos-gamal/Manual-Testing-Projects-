You can find the most updated Test Cases through this link: https://docs.google.com/spreadsheets/d/15E6ma9DcaNxY5J1z8exii3GamASvALmyOg2MMRb8r7g/edit?usp=sharing
user story:
1. ATM Withdraw 
As a bank customer,
I want to withdraw cash from an ATM,
So that I can access physical money when needed.
 
Acceptance Criteria:
 
Authenticate the user via card and PIN.
Ensure the withdrawal amount is:
A multiple of 10 LE.
Between 100 LE (minimum) and 10,000 LE (maximum per transaction).
Does not exceed the daily limit of 50,000 LE.
Deduct the withdrawn amount from the account balance only if cash is dispensed successfully.
Display an error message for invalid amounts or insufficient funds.
Provide a receipt (optional for the user).
