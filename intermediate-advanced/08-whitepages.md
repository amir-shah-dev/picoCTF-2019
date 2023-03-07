# WhitePages

## Objectives

> - Find hidden data in file
1. open the file whitepages.txt. Is there anything in the file


<details>
<summary>Hint?</summary>
<br>

Characters in the file may not be visible...

</details>

2. If there are characters in the file what could they represent? Could we write a quick Python script to replace the characters? 

<details>
<summary>Hint?</summary>
<br>

Try converting to binary where each of the different characters maps to a one or a zero. We know that some of the characters are spaces

Psuedocode:
~~~~
text = '                             ...'
output = ''
for char in text:
    if char == ' ':
        output = output + '1'
    else:
        output = output + '0'
print(output)
~~~~

</details>

3. Convert to Ascii

<details>
<summary>Hint?</summary>
<br>
You can do this by copying the script output into a tool such as Cyberchef.
https://gchq.github.io/CyberChef/

</details>
