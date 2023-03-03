# Glory of the Garden

## Objectives

>- Uncover a hidden message stored within an image

1. Begin by downloading the image using the picoCTF webshell through the command below. 
You can also download the image to view directly from your browser, where you will notice the flag is not able to be seen visually
```console
wget https://jupiter.challenges.picoctf.org/static/d0e1ffb10fc0017c6a82c57900f3ffe3/garden.jpg
```

2. A common place to look for flags within an image is by analyzing the bits making up the image
<details>
<summary>Hint?</summary>
<br>
Based on the hint provided to us by the challenge, we should start with a Hex dump. This is where the binary contents of the image are displayed in hexadecimal
</details>

3. To peform a hex dump on the image within the webshell, we will use the command `xxd` as seen below. At the very bottom of the dump you should see that the flag has indeed been encoded in hexadecimal within the image file, with the ascii output corresponding to our flag!
```console
xxd garden.jpg
````
