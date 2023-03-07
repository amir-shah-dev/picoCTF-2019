# where are the robots
## Objectives
> - Understanding how the robots.txt file works.

This challenge teaches us about the **robotx.txt** file. This file is widely used to tell automated web crawlers which sites they are allowed to crawl, usually to avoid overloading the website with requests. This file is usually located at the root directory of the server’s filesystem, so to find it just add /robots.txt at the end of a URL. You can find an example in [bbc.co.uk/robots.txt](bbc.co.uk/robots.txt), where the robots.txt file offers sitemaps that basically contain a repository of links that can be navigated, but also has a Disallow list to stop crawlers accessing certain ones.
<details>
<summary>Hint</summary>
<br>
In this case, if we visit [https://jupiter.challenges.picoctf.org/problem/56830/](https://jupiter.challenges.picoctf.org/problem/56830/) we will get very little information, but if we try with [https://jupiter.challenges.picoctf.org/problem/56830/robots.txt](https://jupiter.challenges.picoctf.org/problem/56830/robots.txt) we find a suspicious site: /1bb4c.html, which is our clue. Visiting the site [https://jupiter.challenges.picoctf.org/problem/56830/1bb4c.html](https://jupiter.challenges.picoctf.org/problem/56830/1bb4c.html) gives us the flag.
</details>