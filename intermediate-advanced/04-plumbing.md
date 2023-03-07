# plumbing

## Objectives

> - Using pipes
> - Using a command utility for searching data sets
> 
1. Start by connecting to the provided server using netcat (your server number will be different)
  ```console
  nc jupiter.challenges.picoctf.org 14291
  ```
2. The output contains numerous lines of filler messages, which prevent you from being able to locate the printed flag. You will need to combine the server output with some sort of data matching to retrieve the flag.

<details>
<summary>Hint?</summary>
<br>
To combine two commands in one line, it is necessary to use a pipe. A pipe is designated in commands by the vertical bar character, with general syntax:

```console
  command_1 | command_2 [| command_3 . . . ]
```
</details>
  
<details>
<summary>Hint?</summary>
<br>
  
A command used for data matching you may have encountered in previous CTF challenges is `grep`. To use grep:

```console
  grep <string>
```
  
</details>

4. To retrieve the correct output from the server, remember the standard format of flags on picoCTF, and search for any lines containing such format
5. Given that all picoCTF flags begin with "picoCTF", you can use grep as you connect to the challenge server to print the required flag (remember your server number will be different)
```console
  nc jupiter.challenges.picoctf.org 14291 | grep picoCTF
```
