# The Numbers

## Objectives
>- Use a cipher to uncover a hidden message and recover the flag

1. Begin by downloading and opening the .png file from the challenge. You should see a bunch of numbers written in the format of a standard picoCTF flag
2. To recover the flag, you will need to find out what cipher has been used to encrypt the flag. Once found, an online converter can easily be found for deciphering.

<details>
<summary>Hint?</summary>
<br>
Given that the format of a standard picoCTF flag is preserved, i.e. there are 7 numbers prior to the "{", which correspond to the "picoCTF" string before every flag, this can be a starting point for uncovering the cipher used by the challenge
</details>

3. Once you have found the cipher and used an online converter, the true message of the flag should be revealed!
<details>
<summary>Answer:</summary>
<br>
16 9 3 15 3 20 6 { 20 8 5 14 21 13 2 5 18 19 13 1 19 15 14 } 
	
The number above is encrypted using a [Substitution Cipher](https://www.dcode.fr/letter-number-cipher) based on Letter Number (A1Z26) A=1, B=2, C=3…..
	
	
16 9 3 15 3 20 6 => PICOCTF

20 8 5 14 21 13 2 5 18 19 13 1 19 15 14 => THENUMBERSMASON

Flag: PICOCTF{THENUMBERSMASON}
</details>
