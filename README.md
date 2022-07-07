# Creating-a-scheduled-query-rule

# Why do we create query rules?
- We create rules for certain use cases.
- For example, search for any anomolous behavior and raise an alert.
- Users can define their own query and raise an alert based on the outcome of the rule.

# Sign-in failed query rule
- In tactics and techniques - select Credential Access and Forced Authentication
- We want to see if the sign in code is not equal to 0. It means that there was a sign-in failure.
- Essentially, you are querying the LAW.
- 


# Simulate a sign-in to see if an alert and incident was create
- The rule will run every 5 minutes and will generate an alert if there is more than 1 failed log in.
