# Creating-a-scheduled-query-rule

# Why do we create query rules?
- We create rules for certain use cases.
- For example, search for any anomolous behavior and raise an alert.
- Users can define their own query and raise an alert based on the outcome of the rule.

# Sign-in failed query rule
- In tactics and techniques - select Credential Access and Forced Authentication
- The tactics and techniques section are based on the MITRE Attack framework. The tactics on the website is listed in Azure.
- These tactics are documented and help infosec professionals understand each attack.
- We want to see if the sign in code is not equal to 0. It means that there was a sign-in failure.
- Essentially, you are querying the LAW.
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/177671276-a373d8d4-ac8b-4095-a7ee-12805b2890b0.png" height="75%" width="75%" alt="Azure LAW"/>

<p/>

# The rule will run every 5 minutes and will generate an alert if there is more than 1 failed log in.
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/177671291-d00b6aca-3a08-4fd6-a3d5-382a79beb2d1.png" height="75%" width="75%" alt="Azure LAW"/>

<p/>

# Our rule

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/177671928-dd18af7d-d9d0-42c3-b6ff-d0905497d254.png" height="75%" width="75%" alt="Azure LAW"/>

<p/>

# Overview of the LAW in Sentinel before failed sign-ins
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/177672075-72f1078c-869c-43c4-8a94-891a85d3e155.png" height="75%" width="75%" alt="Azure LAW"/>

<p/>


# Simulate a sign-in to see if an alert and incident was create
- I failed to sign-in about 4 times in the lebron james account.
- Alerts should be generated.
<p align="center">
  
<img src="" height="75%" width="75%" alt="Azure LAW"/>

<p/>
