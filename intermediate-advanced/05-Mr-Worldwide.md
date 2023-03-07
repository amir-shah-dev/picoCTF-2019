# Mr-Worldwide

## Objectives

>- Decipher a hidden message by recognising and using the format of the message
>- Recover the flag by looking at common patterns used in crytography

1. Begin by downloading and opening the text file. Inside you should see "picoCTF{" followed by a long string of numbers which you will need to decipher

<details>
<summary>Hint?</summary>
<br>
What do these numbers translate to? A big clue comes from the fact that the numbers are in pairs, seperated by commas and enclosed in brackets. This is the common format for geographical coordinates, as hinted to by the name of the challenge.
</details>

2. Once you have found the associated locations for the various coordinates, you must find a way of relating it back to format of a picoCTF flag

<details>
<summary>Hint?</summary>
<br>
You will have likely wrote down the general city/locations for each of the coordinates, however these combined can't make up the flag given the standard flag is no longer than 15 characters. There is something that can be used from each of the locations however, which may be more easily visible when listing the ciies down vertically. Extra Hint: Use the city names associated with each coordinate
</details>

3. You should see that each location helps build up the flag and allow you to finish the challenge!
<details>
<summary>Answer</summary>
<br>
Coordenates	City, Country	Letter
<br>(35.028309, 135.753082)	Kyoto, Japan	K
<br>(46.469391, 30.740883) 	Odessa, Ukraine	O
<br>(39.758949, -84.191605) 	Dayton, United States	D
<br>(41.015137, 28.979530)	Istanbul, Turkey	I
<br>(24.466667, 54.366669)	Abu Dhabi, UAE	A
<br>(3.140853, 101.693207) 	Kuala Lumpur, Malaysia	K
<br>(9.005401, 38.763611)	Addis Ababa, Ethiopia	A
<br>(-3.989038, -79.203560)	Loja, Ecuador	L
<br>(52.377956, 4.897070)	Amsterdam, Netherlands	A
<br>(41.085651, -73.858467)	Sleepy Hollow, USA	S
<br>(57.790001, -152.407227)	Kodiak, United States	K
<br>(31.205753, 29.924526)	Alexandria, Egypt  	A
	
<br>The flag is: picoCTF{KODIAK_ALASKA}
</details>
