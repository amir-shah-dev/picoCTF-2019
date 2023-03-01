# based

## Objectives

> - Convert between different data encodings
> - Recognise binary, hexadecimal, octal, decimal

1. Start by connecting to the server using netcat (your server number will be different)
  ```console
  nc jupiter.challenges.picoctf.org 15130
  ```
2. You should then see a string in either binary, hexadecimal, octal, decimal. You will have 45 seconds to identify which this is and convert it back into text. The quickest way is to find a web-based decoder. Here is an example: https://www.rapidtables.com/convert/number/binary-to-ascii.html
3. Entering the decoded text will lead to another random string being generated. You will need to convert this back into text to proceed once again. 
4. Once you have successfully provided the right answer three times in a row, within the time constraints, you will receive the flag.
