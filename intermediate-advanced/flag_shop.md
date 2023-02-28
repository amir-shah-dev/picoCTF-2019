# flag_shop

## Objectives

> - Analyse code and create a integer overflow

1. Look at the code in `store.c`, by opening it up in your terminal. What options would you have to select to _buy_ the flag?


<details>
<summary>Hint?</summary>
<br>

You would have to enter the numbers when prompted in the following order: `2, 2, 1`.

Just like you would when calling an automated telephone line.

</details>

2. So it seems that we don't have enough funds to purchase the flag. How could we increase our balance? Notice anything in the code that we could utilise?

<details>
<summary>Hint?</summary>
<br>

Look at line 42: `account_balance = account_balance - total_cost;`

We can use `-` to our advantage by inducing an overflow such that if we buy many flags, the `total_cost` integer will wrap around and become negative. This trick will actually increase our total balance, enought to buy the actual flag!

See [here](https://www.welivesecurity.com/2022/02/21/integer-overflow-how-it-occur-can-be-prevented/) for more info on _integer overflow_

</details>