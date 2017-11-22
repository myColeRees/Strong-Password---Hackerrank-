# Strong-Password---Hackerrank-
Practicing version control using a Hackerrank puzzle and Java 8

** so the idea in practicing is not to change the whole code and get it to work right away, but to change different parts of it to see what happens with compatibility. It doesn't have to be a big change or have to work. 

The puzzle is located here: https://www.hackerrank.com/contests/hourrank-24/challenges/strong-password

This is not the puzzle description; you can read that in the link above. This is just a collection of thoughts to think about the algorithm.

There are two main concerns: is the password long enough? if not add more characters.
is the password diverse enough? if not add a specific type of character for each one not represented in the sample. 

If the length is already 6 characters, but isn't diverse enough, the minimum to add is the missing character total.
If the length is shorter than 6, the minimum will be the 6 - (the length + the missing character number) + the missing character number (I think)

The length is given by input. The password is given by input.

This can be used in the solution method:
numbers = "0123456789"
lower_case = "abcdefghijklmnopqrstuvwxyz"
upper_case = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
special_characters = "!@#$%^&*()-+"
