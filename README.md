# ad361-lab02-black-box-testing

## Step 1: Select a Website

Website Name: Amazon

Website URL: https://www.amazon.com

Feature(s) to Test:

Amazon Account Sign-In
User Authentication

Testing Approach: This lab uses black-box testing techniques to evaluate the Amazon Account Sign-In feature without viewing or using the website's source code.

## Step 2: Equivalence Partitioning
### Feature Tested

Amazon Account Sign-In

The purpose of this test is to verify that users can successfully sign in with valid credentials and receive appropriate feedback when invalid credentials are used.

### Valid Partitions
<img width="767" height="150" alt="image" src="https://github.com/user-attachments/assets/5118ddee-59fd-476c-ae6b-2984785aed7b" />

### Invalid Partitions
<img width="767" height="221" alt="image" src="https://github.com/user-attachments/assets/a12315a5-ae55-460c-87be-90d473319894" />

### Conclusion

Equivalence partitioning reduces the number of tests required by grouping similar inputs into categories and selecting one representative value from each category.

## Step 3: Decision Table Testing
### Feature Tested

Amazon Account Sign-In

### Conditions
Account exists?
Password is correct?
### Actions
Allow sign-in
Display error message
### Decision Table
<img width="764" height="183" alt="image" src="https://github.com/user-attachments/assets/2c6d4219-65d4-4e0c-ab9f-1c73942ceb12" />

### Test Cases
<img width="770" height="185" alt="image" src="https://github.com/user-attachments/assets/3e43261f-5677-4017-9339-0af25a0bc4a7" />

### Conclusion

Decision table testing ensures that all combinations of conditions are evaluated and that the correct action occurs for each possible scenario.

## Step 4: State Transition Testing
### Feature Tested

Amazon Account Sign-In

### States
Signed Out
Entering Credentials
Signed In
Authentication Error
### Events
User selects Sign In
User enters valid credentials
User enters invalid credentials
User retries sign-in
User signs out
### State Transition Table
<img width="759" height="257" alt="image" src="https://github.com/user-attachments/assets/6128b374-d45e-4dd0-bb54-3b8ccfa06963" />
Test Cases
<img width="768" height="224" alt="image" src="https://github.com/user-attachments/assets/78fa52ee-82e2-4ab2-b897-f1370b95c463" />
Conclusion

State transition testing verifies that the sign-in process moves correctly between states and properly handles both valid and invalid user actions.
