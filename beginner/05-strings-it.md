# Strings it

## Objectives

> - Use the `strings` command to search for flag

1. Use the wget command to download the file
<details>
<summary>Hint?</summary>
<br>
Right click on the link of the file you wish to download. Then simply run the following in the terminal 'wget <link_to_file>'

</details>

2. So you may be thinking that you could do the same thing you did in challenge #3 to find the flag. Unfortunately this time the file is a binary executable. You can check this by running the command `file strings`. You need to instead use a another tool to search for printable strings in the program.

<details>
<summary>Hint?</summary>
<br>

Remember all flags are of the same format, `picoCTF{}`

Just as you did before, you can pipe the output of the `strings` command with grep to retrieve the flag.
See below:

`strings strings | grep picoCTF`

</details>
