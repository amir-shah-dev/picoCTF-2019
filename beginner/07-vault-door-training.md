# vault-door-training

## Objectives

> - Inspect some basic java code

1. In order to run the program in `VaultDoorTraining.java`, you must first compile it. This can be done with the `javac` command. Lets try it! Run the following command: `javac VaultDoorTraining.java`. Notice now that you have a `VaultDoorTraining.class` file in your directory. To run the program just run the following: `java VaultDoorTraining`. Great job, lets enter any password in the prompt. It looks like we can't guess our way in, let's instead inspect the code and find any clues!
2. Open the `VaultDoorTraining.java` and let's inspect it. Notice any clues?
<details>
<summary>Hint?</summary>
<br>

Try to understand what each line of the code is doing. If you are stuck, please reach out to any of the helpers present.

It appears that the password is present on `line 23` and stored in plaintext!

</details>

3. Enter the correct password to the vault to retrieve the flag.
<details>
<summary>Hint?</summary>
<br>

Pay attention to `line 9`, the vault password expected must be in the correct format which in this case is `picoCTF{...}`
</details>
