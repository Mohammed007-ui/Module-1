# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the smallest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum.  
   - Else, if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum.  
   - Otherwise, `num3` is the minimum.  
4. Print the minimum value along with the input numbers in the format:  
   `"The minimum of num1, num2, num3 is min_num."`  
5. Terminate the program.

## PROGRAM
```python
# Reg.No: 212223060161
# Name: Mohammed Ali.S

# Read three numbers from the user
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
num3 = int(input("Enter third number: "))

# Find minimum using nested ternary operator
min_num = num1 if (num1 <= num2 and num1 <= num3) else num2 if (num2 <= num1 and num2 <= num3) else num3

# Display the result
print(f"The minimum of {num1}, {num2}, {num3} is {min_num}")

```

## OUTPUT

![image](https://github.com/user-attachments/assets/b0c1d157-da07-430d-97b5-f57ad69c54ef)

## RESULT

Thus, the Python program to find the minimum of three numbers using a conditional expression was written and executed successfully.

