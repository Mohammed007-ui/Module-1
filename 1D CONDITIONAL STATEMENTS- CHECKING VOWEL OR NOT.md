## Experiment No: 1d – Conditional Statements- Checking Vowel or not

## AIM  
To Write a Python program to check whether the given character is a vowel or not using if..else statement
## ALGORITHM  
1. Begin the program.  
2. Take a character input from the user
3. Convert the character to lowercase
4. Check if the lowercase character is one of the vowels: 'a', 'e', 'i', 'o', 'u'
5. If it is a vowel, display "The given character is a vowel"
6. Otherwise, display "The given character is NOT a vowel"
4. Terminate the program.

## PROGRAM
```python
# Reg.No: 212223060161
# Name: Mohammed Ali.S

# Get a character input from the user
ch = input("Enter a character: ")

# Convert to lowercase for uniform comparison
ch = ch.lower()

# Check if the character is a vowel
if ch in ['a', 'e', 'i', 'o', 'u']:
    print(ch, "is a vowel.")
else:
    print(ch, "is not a vowel.")

```

## OUTPUT

![image](https://github.com/user-attachments/assets/d16dba34-c490-4887-9309-f5d992bfc823)

## RESULT

Thus, the Python program to check whether a given character is a vowel using if..else was written and executed successfully.

