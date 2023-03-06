# Dont-use-client-side

## Objectives

> - Bypass weak authentication
1. Navigate to the link - What do you see?


<details>
<summary>Hint?</summary>
<br>

It might help to INSPECT the page closely

</details>

2. How is the login page vulnerable? 

<details>
<summary>Hint?</summary>
<br>

Use inspect element to view the content of the JavaScript function verify.

</details>

3. Extract obfuscated password

<details>
<summary>Hint?</summary>
<br>
You can see that the function matches your entered credential in 4 character sections. The 4 character matches are made up of a set of if statements in no particular order, this obfuscates the function to a degree. Looking at the if statements we can see which 4 characters are being matched in which statement. Analysing each if statement we can work out the correct credential. 

When the correct credential is entered, the user is served the message: Password Verified. 

The challenge flag is the password. 

</details>
