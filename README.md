Introduction

This document serves as a comprehensive guide to the Python code snippets you've explored. It explains the functionality of each code block and highlights key concepts in Python programming.

Code Snippets and Explanations

Variable Assignment and Printing:

Python
a = "Why are u fine?"
print(a)
Use code with caution.

a is assigned the string "Why are u fine?".
print(a) displays the assigned string to the console.
Personalized Greeting with Variable:

Python
name = "Eric"
print(f"Hi {name.lower()} how are you?")
Use code with caution.

A variable name stores the string "Eric".
f-strings are used to create a personalized greeting by inserting the name in lowercase format using name.lower().
Name Case Exploration:

Python
name = "Eric"
print(f"Hi {name.lower()} how are you?")  # Lowercase
print(f"Hi {name.upper()} how are you?")  # Uppercase
print(f"Hi {name.title()} how are you?")  # Title case (first letter capitalized)
Use code with caution.

This code demonstrates how to utilize string methods like lower(), upper(), and title() to transform a name into different capitalization styles.
Famous Quote:

Python
# Replace with your favorite quote and author
quote = "The important thing is not to stop questioning. Curiosity has its own reason for existing. - Albert Einstein"
print(quote)
Use code with caution.

Customize this section by replacing the placeholder text with a quote you admire and its author. Double quotes (") are used to enclose the quote itself.
Temperature Display:

Python
temperature = 25
print(f"The current temperature is {temperature} degrees.")
Use code with caution.

An integer variable temperature stores the value 25.
An f-string displays the temperature reading in a formatted message.
Multi-Line Poem:

Python
poem = """
    PIAIC was found out by Mr.Zia,
    Their is a guy Umair khan, sir jahanzeb knows him well, with Mustaches in 3rd quarter
    He works daya and night, completes the projects,  presented custom GPTS to Zia Sahab.
    But Zia sahab never thinks of inducting him as an instructor at PIAIC,
    He participated in Hackathons, made projects on LinkedIns, It is a request to sir Jahanzeb,
    convey my msg to sir zia, plz consider my brother for the post of instructor at PIAIC.

    """

print(poem)
Use code with caution.

Triple quotes (```) are used to create a multi-line string containing the poem.
The poem is printed, preserving the line breaks.
Score Variable:

Python
score = 100
print(score)
Use code with caution.

score is assigned the integer value 100.
print(score) outputs the score.
String Transformation:

Python
a = "PYTHON PROGRAMMING"
print(a.title())  # Title case
print(a.lower())  # Lowercase
print(a.upper())  # Uppercase
Use code with caution.

The string variable a holds "PYTHON PROGRAMMING".
a.title() prints the string in title case.
a.lower() prints the string in lowercase.
a.upper() prints the string in uppercase.
Whitespace Handling:

Python
name = "  Muhammad   "  # Includes tabs and spaces
print(name)
print(name.strip())  # Removes leading and trailing whitespace
Use code with caution.

name is assigned a string with leading and trailing whitespace characters ().
print(name) displays the string with the whitespace.
print(name.strip()) removes the whitespace from the beginning and end, producing "Muhammad".
Variable Swapping:

Python
x = "How"
y = "you"

temp = x
x = y
y = temp
