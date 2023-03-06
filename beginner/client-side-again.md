# Dont-use-client-side

## Objectives

> - Bypass weak authentication again
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
the function is much more obfuscated. However, the challenge can be completed by ignoring the majority of the function. 

The top line of the function declares a list, function reconstructs some of the items in this list into the correct credential. We know that flags follow the format picoCTF{...}. 

Appending the correct subset of the strings gets us the correct credential, and thus the flag. 

</details>
