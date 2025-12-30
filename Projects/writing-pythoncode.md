## Task 1

In this lab I’m working with a notebook-based coding environment consisting of two types of cells: (1) text cells, also known as markdown cells, and (2) code cells.
Markdown cells allow you to write plain text and format it in the markdown language, used for formatting plain text in text editors and code editors. As an example, I can use markdown to make headers, bold or italicize words, format text as code, add hyperlinks, and more.
For this task, I must write something into the following markdown cell and replace the "[Double-click to edit this markdown cell and write something here.]" with my own text. Then, I must press the Shift and Enter keys (or on some keyboards, the Shift and Return keys) to display my text.
 
## Task 2

In Python notebooks, the code cells allow me to write code comments and code in Python.
To run a code cell, I must first place my cursor on the cell. Then, I can either click on the play icon, or press the Shift and Enter keys.
For this task, I ran the following code cell as is and observed the output.

# This cell displays "Hello world!"

 print("Hello world!")
 
Question 1
What do you observe about the output after you ran the code cell?
The output shows the statement Hello world! on the screen.

## Task 3
By writing code comments I can document the intention behind code, a standard commonly used in workflow. Writing comments that accompany code allows you to keep track of the technical decisions you've made in your project. This makes it easier for an analyst to read and revisit the code in order to understand what it does and why the analyst took certain approaches.
For this task, I ran the following code cell as is and observed the output.

# In Python, comments do not get displayed
# This code cell contains only comments

Question 2
What do you observe about the output after you ran the cell above?
There is no output because the code cell above consists of two code comments, each comment starting with a hash symbol (#). And Python ignores comments when is executed. Code comments aren't interpreted by the computer; they're interpreted by analysts.

## Task 4
For this task, I added a comment at the beginning of the code cell presented, describing what the code is doing. My comment will say, # This cell displays "I am using Python.". Be sure to replace the # YOUR COMMENT HERE with your own comment before running the following cell.

# This cell displays "I am using Python."

print("I am using Python.")

Question 3

What do you observe about the output after you ran the cell above?
The output is “I am using Python.” The quotes around a string do not appear in the output when the string is displayed.

## Task 5

As I am using Python, for this task, I used print() to display the message "I am a security analyst." by placing that message in the parentheses. I replaced the ### YOUR CODE HERE ### with my own code before running the following code cell.

# This cell displays "I am a security analyst."

print("I am a security analyst.")

Question 4

What do you observe about the output after you ran the cell above?
The output is “I am a security analyst.” The quotes around a string do not appear in the output when the string is displayed.

## Task 6

For this task, I wrote a print() statement to display the string "Python is useful for security!" I replaced the ### YOUR CODE HERE ### with my own code before running the following code cell.

# This cell displays "Python is useful for security!"

print("Python is useful for security!")

Question 5

What do you observe about the output after you ran the cell above?
The output is “Python is useful for security!” The quotes around a string do not appear in the output when the string is displayed.

## Task 7

In this task, I combined all the print() statements I've encountered and written in this lab up to this point, into one code cell.
I completed the following code with the remaining messages. I replaced each ### YOUR CODE HERE ### with my own code before running the following cell.

# This cell displays all the statements written so far

print("Hello world!")
print("I am using Python.")
print("I am a security analyst.")
print("Python is useful for security!")
 
Question 6

What do you observe about the output after you ran the cell above?
Each line in the output resulted from stating “print()” in the code. “Hello world!” appears in the first line of the output, “I am using Python.” appears on the second line of the output, “I am a security analyst.” appears third, and “Python is useful for security!” appears on the fourth. Here Python interprets and executes code in order.

## Conclusion

What are your key takeaways from this lab?

- It's helpful to use code comments to document the decisions made as the analyst code.
- Computers ignore code comments; they're read by the analyst team to understand the intentions behind the code.
- I can write comments in Python using the hash symbol (#).
- I can use “print()” in Python to display information to the screen.
- When you use “print()” to display a string, the quotes around the string do not appear in the output on the screen.
 
