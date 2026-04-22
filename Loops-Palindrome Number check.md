## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** .

## 🧠 Algorithm
Start.

Input: Receive an integer from the user (let's call it a).

String Conversion: Convert the integer a into a string so it can be broken down into individual characters.

List Creation: Iterate through each character in the string, convert it back to an integer, and store it in a list d.

Reversal Comparison: * Create a reversed version of list d (using the slice [::-1]).

Compare the original list d with the reversed list.

Decision:

If they are identical, the number reads the same forward and backward. Print that it is a Palindrome.

Else, print that it is not a Palindrome.

End.

## 🧾 Program
```
a=int(input())
d=[int(i) for i in str(a)]
if (d==d[:: -1]):
    print(f"The given number {a} is a Palindrome")
else:
    print(f"The given number {a} is not a palindrome")
```
## Output


## Result
Python program that checks whether a given number is a **palindrome** was successful.
