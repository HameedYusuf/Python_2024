## user_input.py

This program collects the user's name, age, and location, and then displays a personalized message.

**Instructions:**

1. Save this content as a new file named `user_input.py`.
2. Run the program using Python. (For example, in your terminal, navigate to the directory where you saved the file and run `python user_input.py`.)

**Code:**

```python
# Get user's name
name = input("What is your name? ")

# Get user's age (convert input to integer)
age = int(input("How old are you? "))

# Get user's location
location = input("Where do you live? ")

# Print personalized message
print(f"Hello {name}, you are {age} years old and live in {location}.")
```

**Explanation:**

- The program uses the `input()` function three times to collect user input for name, age, and location.
- The `int()` function converts the user's input for age from a string (what `input()` always returns) to an integer.
- String formatting (f-strings in this case) is used to create the personalized message by embedding variables within curly braces `{}`.

**Running the program:**

When you run the program, you'll be prompted to enter your name, age, and location. After providing the information, the program will display a message like this:

```
Hello John, you are 30 years old and live in New York.
```
