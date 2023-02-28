# what's a net cat?

## Objectives

> - Use nc to open up a remote connection

1. The challenge states that you should use the `nc` (netcat) command. Try running `nc --help` and see if you can work out how you would run the tool with the given details in the challenge.
<details>
<summary>Hint?</summary>
<br>

At its most basid to run `nc` you need to provide a destination address and a port number on that remote adress you would like to access. So the command would go as follows:

`nc jupiter.challenges.picoctf.org 25103`

Don't forget to close the connection by hitting `CTRL+C`

</details>
