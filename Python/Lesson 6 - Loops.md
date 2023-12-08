
## Exercise: Looping - Multiplication Table
### Objective: Use a loop to print a multiplication table for a given number.

```
# Ask the user for a number
number = int(input("Enter a number to see its multiplication table: "))

# Print the multiplication table for the number
for i in range(1, 11):
    print(number, "x", i, "=", number * i)
```
