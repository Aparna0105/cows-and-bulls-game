# cows-and-bulls-game
EXPLAINATION:
Cows and Bulls is a pen and paper code-breaking game usually played between 2 players. In this, a player tries to guess a secret code number chosen by the second player. The rules are as follows:

1)A player will create a secret code, usually a 4-digit number.  This number should have no repeated digits.

2)Another player makes a guess (4 digit number) to crack the secret number. Upon making a guess, 2 hints will be provided- Cows and Bulls.

3)Bulls indicate the number of correct digits in the correct position and cows indicates the number of correct digits in the wrong position. For example, if the secret code is 1234 and the guessed number is 1246 then we have 2 BULLS (for the exact matches of digits 1 and 2) and 1 COW (for the match of digit 4 in the wrong position)

4)The player keeps on guessing until the secret code is cracked. The player who guesses in the minimum number of tries wins.
APPROACH:
To create this game in Python, the computer generates a secret code and the user will have to guess the code. Break it down into these blocks:

1)Generate a secret code- Generate a random 4-digit number and check that it does not have any repeated digits.

2)Generate hint or response- Take the generated 4-digit secret number and the guessed number (input). Find the common digits with exact matches (bulls) and the common digits in the wrong position (cows). Repeat with each guess until you have 4 bulls (an exact match) or you run out of tries.

Constraint: The secret code and the guessed code should be of 4-digits (between 1000 and 9999) and have no repeated numbers.
