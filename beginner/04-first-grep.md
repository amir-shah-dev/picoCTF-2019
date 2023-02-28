# First Grep

## Objectives

> - Use grep to search and find the flag in a file

1. Use the wget command to download the file
<details>
<summary>Hint?</summary>
<br>
Right click on the link of the file you wish to download. Then simply run the following in the terminal 'wget <link_to_file>'

</details>

2. The file you have dowloaded is extremely long so manually searching for the flag will be impossible. See for yourself, run `cat file`. If we had a way to search what would we enter into the tool to find the flag, is there anything common found in all the flags that we can search for?

<details>
<summary>Hint?</summary>
<br>

Remember all flags are of the same format, `picoCTF{}`
So why not search for `picoCTF` and see what turns up?
</details>

3. After you have decided on the string you would like to search for, then you could use any command line linux tool to search the file. A hint would be to use the tool mentioned in the name of the challenge (`grep`).

<details>
<summary>Hint?</summary>
<br>

The easiest tool to use would be `grep`. To search `grep` requires input which can be passed via a concept know as `piping`. This is where the output of one command is chained together and passed as the input of another commnand usually with this symbol `|`. So if we chain the output of the `cat` command with `grep` we should get the flag!. See below:

`cat file | grep picoCTF`

</details>
