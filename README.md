# password-checker
A python program which, checks a given password or string, and rate its degree of safety depending on several factors.

It rates by star(*), and each of the bellow factors if are True, it adds an star.

- If its length is equal to or more than 8
- If it includes number
- If it includes letters
- If it includes both capital and small letters
- if it includes special characters

3 examples:

enter a password:
-password
**

enter a password:
-pass
*

enter a password:
-P@s$w0rd
*****
