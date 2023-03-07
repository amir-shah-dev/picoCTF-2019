# logon
## Objectives
> - Know how to change cookies in your browser.

This challenge can be a bit confusing when it comes to knowing what it is we have to do. Visiting the site provided gives us a login prompt that asks for a username and a password. If we try to log in as Joe, as instructed in the challenge, we will not get anywhere, because we do not know the password to this user and techniques like SQL injection do not seem to work here. Instead, we’ll find that the website doesn’t check the credentials for any other user, so we can write anything in the username field and log in. 
<details>
<summary>Hint</summary>
<br>
Once in, we are told that our success is short-lived, as we can’t see the flag. However, inspecting the cookies we will see the ‘admin’ cookie has been set with a `False` value. Changing this to `True` and reloading the page gets us the flag.
Note - To inspect our cookies we can do the following:

- Chrome: Right click > Inspect > Application > Cookies on the left-hand side
- Firefox: Right click > Inspect > Storage > Cookies on the left-hand side
</details>