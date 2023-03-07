# picobrowser
## Objectives
> - Understanding and knowing how to modify the User Agent value of a browser.

This challenge introduces the concept of user agent. Each browser has its own unique user agent field, which can be read by websites to know when it needs to render the mobile phone version of the site, for example. However, this value can actually be changed by the user to whatever they want.
<details>
<summary>Hint</summary>
<br>
If we visit the website https://jupiter.challenges.picoctf.org/problem/28921/ and click on the green Flag button, we will get a message stating we are not picobrowser, so let’s solve that! Let’s change our user agent string to `picobrowser` by using one of the methods below and now clicking on the green Flag button takes us straight to the prize.

Note – To change our user agent we can do the following:

- Chrome: Right click > Inspect > 3 dots at the right > More Tools > Network conditions 
\> Uncheck ‘Use browser default’ > Write your own value
- Firefox: Visit the site ‘about:config’ in your address bar and dismiss the warning > type ‘general.useragent.override’, select ‘String’ for its value and click on the + sign > Enter your desired value (remember to delete this once you are done!)
</details>