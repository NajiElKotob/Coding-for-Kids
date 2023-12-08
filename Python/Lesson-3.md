# Python for Kids

## Lesson 3: Conditional Statements

### Excercise 1 | Introduce if statements and comparisons.


```python

# Greater or Less Than 5

# Ask the user for a number
number = int(input("Enter a number: "))

# Check if the number is greater than 5
if number > 5:
    print("Your number is greater than 5!")
else:
    print("Your number is 5 or less!")

```

-----

### Exercise 2 | Weather Advice - Provide advice based on the temperature
```
# Ask the user for the current temperature
temperature = int(input("What is the temperature right now? "))

# Give advice based on the temperature
# Check if the temperature is above 30 degrees
if temperature > 30:
    print("It's hot outside! Remember to stay hydrated.")
# Check if the temperature is between 21 and 30 degrees
elif temperature > 20:
    print("It's a nice day. Enjoy the outdoors!")
# Check if the temperature is between 11 and 20 degrees
elif temperature > 10:
    print("It might be a bit chilly. Wear a jacket.")
# For temperatures 10 degrees or below
else:
    print("It's cold! Stay warm and consider wearing a coat.")

```

