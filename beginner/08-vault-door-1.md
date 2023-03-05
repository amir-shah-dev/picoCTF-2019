# vault-door-1

## Objectives

> - Inspect some _more_ java code

1. Similar to the last challenge, you first need to compile the program with the following command: `javac VaultDoor1.java`. To run the program just run the following: `java VaultDoor1`. It seems like the program requires a password in order to retrieve the flag. Let's instead inspect the code and find any clues!
2. Open the `VaultDoor1.java` and let's inspect it. Notice any clues?
<details>
<summary>Hint?</summary>
<br>

Try to understand what each line of the code is doing. If you are stuck, please reach out to any of the helpers present.

Looks like the function at line `line 22` is checking the password. If you look closely the password is still stored in plaintext for all to see. The programmer has slighlty obfuscated it by separating the character. Try piecing the characters together in order, a pen and paper might help!

</details>

3. Enter the correct password to the vault to retrieve the flag.
<details>
<summary>Hint?</summary>
<br>

Pay attention to `line 9`, the vault password expected must be in the correct format which in this case is `picoCTF{...}`
</details>
