## Task 1

In this task, there is a device only users specified on an allow list can access, and its device ID is "72e08x0".
In the following code cell, I assigned this value to a variable named device_id. 
I replaced the ### YOUR CODE HERE ### with my own code before you run the following cell.

# Assign the `device_id` variable to the device ID that only specified users can access

device_id = "72e08x0"

# Display `device_id`

print("72e08x0")

72e08x0

I used quotation marks around the value assigned to the “device_id” variable. Then, I assigned the value "72e08x0" to the variable “device_id”. To do this, I placed the value to right of the = operator. In order to display the contents of “device_id”, I placed the name of this variable inside the “print()” function.

## Task 2

The variable “device_id” is defined, and now I can return its data type.
I will use a Python function to find the data type of the variable “device_id”. Then I will store the data type in another variable called “device_id_type” for it to display “device_id_type” to examine the output.
I replaced the ### YOUR CODE HERE ### with my own code before running the following cell.

# Assign the `device_id` variable to the device ID that only specified users can access

device_id = "72e08x0"

# Assign `device_id_type` to the data type of `device_id`

device_id_type = type(device_id)

# Display `device_id_type`

print(device_id_type)

The function “type()” allows me to get the data type of a given value. I used “type(device_id)” to get the data type of the device_id variable. In order to display “device_id_type”, I placed the name of this variable inside the “print()” function.

## Question 1

Based on the output above, what do you observe about the data type of “device_id”?
The output the data type of “device_id” is “str”, which means that “device_id” stores a string value.

## Task 3

In this task, I was provided a list of usernames of users allowed to access the device. These  are "madebowa", "jnguyen", "tbecker", "nhersh", and "redwards".
I must create a variable called “username_list” to assign a list with the approved usernames to this variable. Then, display the value of the “username_list” variable.
I replaced each ### YOUR CODE HERE ### with my own code before running the following cell.

# Assign `username_list` to the list of usernames who are allowed to access the device

username_list = ["madebowa", "jnguyen", "tbecker", "nhersh", "redwards"]

# Display `username_list`

print(username_list)

['madebowa', 'jnguyen', 'tbecker', 'nhersh', 'redwards']

In Python, to create a list I must use square brackets and inside the square brackets, I wrote the elements of the list, with a comma between elements. To assign a value, I placed the name of the variable to the left of the = operator, and placed the value to the right of the = operator.

I placed ["madebowa", "jnguyen", "tbecker", "nhersh", "redwards"] to the right of the = operator.
In order to display “username_list”, I placed the name of this variable inside the “print()” function.

## Task 4

In this task, I must find the data type of the “username_list”. I stored the type in a variable called “username_list_type”, and display “username_list_type” to examine the output.
I replaced each ### YOUR CODE HERE ### with my own code before running the following cell.

# Assign `username_list` to the list of usernames who are allowed to access the device

username_list = ["madebowa", "jnguyen", "tbecker", "nhersh", "redwards"]

# Assign `username_list_type` to the data type of `username_list`

username_list_type = type(username_list)

# Display `username_list_type`

print(username_list_type)

The “type()” function allows the analyst to get the data type of a given value. In other words, to get the data type of “username_list”, call the “type()” function and pass in “username_list”.
In Python, print() function is used to display the value of a variable. To display username_list_type, call the print() function and pass in username_list_type.

## Question 2

Based on the output above, what do you observe about the data type of username_list?

The output shows the data type of “username_list” is “list”, which means that “username_list” stores a list.

## Task 5

In this task, I’ve been informed that the previous list is not up-to-date and that there is another employee that now has access to the device. You're given the updated list of usernames with access, including the new employee, as follows: "madebowa", "jnguyen", "tbecker", "nhersh", "redwards", and "lpope".
I reassigned the variable username_list to the new list. Run the code to display the list before and after it's been updated to observe the difference.
Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.
# Assign `username_list` to the list of usernames who are allowed to access the device

username_list = ["madebowa", "jnguyen", "tbecker", "nhersh", "redwards"]

# Display `username_list`

print(username_list)

# Assign `username_list` to the updated list of usernames who are allowed to access the device

username_list = ["madebowa", "jnguyen", "tbecker", "nhersh", "redwards", "lpope"]

# Display `username_list`

print(username_list)

['madebowa', 'jnguyen', 'tbecker', 'nhersh', 'redwards']
['madebowa', 'jnguyen', 'tbecker', 'nhersh', 'redwards', 'lpope']
To reassign a variable to a new value in Python, I placed the name of the variable to the left of the = operator, just as you would when assigning the variable for the first time.
To reassign “username_list” to the updated list, place “username_list” to the left of the = operator.

## Question 3

Based on the output above, what do you observe about the contents of username_list?

The output shows the contents of “username_list” were updated after the variable was reassigned to the new list.
The first “print()” call output the original contents of the list. 
The second “print()” call output the updated contents, which includes the newly added username, "lpope".

## Task 6

In this task, I defined a variable called “max_logins” that represents the maximum number of login attempts allowed per user, and the value “3” was stored in this variable. Then, I stored its data type in another variable called “max_logins_type”. Last but not least, I will display “max_logins_type” to examine the output.
I replaced each ### YOUR CODE HERE ### with my code before running the following cell.

# Assign `max_logins` to the value 3

max_logins = 3

# Assign `max_logins_type` to the data type of `max_logins`

max_logins_type = type(max_logins)

# Display `max_login_type`

print(max_logins_type)

<class 'int'>

In Python, when assigning a value an analyst must use the = operator. Then, place the name of the variable to the left of the = operator, and place the value to the right of the = operator.
To assign 3 to “max_logins”, place “max_logins” to the left of the = operator, and place 3 to the right of the = operator.
To assign “max_logins_type”, place “max_logins_type” to the left of the = operator before the type() function call.
In Python, I can use “print()” function to display the value of a variable. To display “max_logins_type”, call print() and pass in “max_logins_type”.

## Question 4

Based on the output above, what do you observe about the data type of max_logins?

The output shows that the data type of “max_logins” is int, which means that “max_logins” stores an integer value.

## Task 7

Here I must define a variable called “login_attempts” that represents the current number of login attempts made by a user. Store the value 2 in this variable. Then, store “login_attempts” data type in a variable called “login_attempts_type”, then I will display “login_attempts_type” to observe the output.
I’ll replace each ### YOUR CODE HERE ### with my own code before running the following cell.

# Assign `login_attempts` to the value 2

login_attempts = 2

# Assign `login_attempts_type` to the data type of `login_attempts`

login_attempts_type = type(login_attempts)

# Display `login_attempts_type`

print(login_attempts_type)

In Python, when assigning a value to a variable an analyst uses the = operator, then place the name of the variable to the left of the = operator, and place the value to the right of the = operator.
To assign 2 to login_attempts, I place login_attempts to the left of the = operator, and place 2 to the right of the = operator.
To assign login_attempts_type, I place login_attempts_type to the left of the = operator, and place a call to the type() function to the right of the = operator.
When calling type(), make sure to pass in login_attempts.
In Python, I can use print() function to display the value of a variable. To display login_attempts_type, call print() and pass in login_attempts_type.

## Question 5

Based on the output above, what do you observe about the data type of login_attempts?

The output shows that the data type of login_attempts is int, which means that login_attempts stores an integer value.

## Task 8

In this task, the analyst must determine the Boolean value that represents whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed.
I replaced each ### YOUR CODE HERE ### with my own code before running the following cell.

# Assign `max_logins` to the value 3

max_logins = 3

# Assign `login_attempts` to the value 2

login_attempts = 2

# Determine whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed,
# and display the resulting Boolean value

print(login_attempts <= max_logins)

True

In Python, I can use the <= comparison operator to determine whether one value is less than or equal to another value. I placed login_attempts to the left of the <= operator, and place max_logins to the right of the <= operator.
To make sure the resulting Boolean value is displayed, I wrote this code inside of the parantheses where print() is called.

## Question 6

What is the output? What does this mean?
The output is True, indicating that login_attempts is less than or equal to max_logins. In other words, the current number of attempts the user has made to log in has not yet exceeded the maximum number of attempts allowed.

## Task 9
In this task, this code continues to check for the Boolean value of whether max_logins is less than or equal to login_attempts. The analyst must reassign other values to login_attempts. I might choose a value that is higher than the maximum number of attempts allowed. 
I replaced replace each ### YOUR CODE HERE ### with my own code before running the following cell.

# Assign `max_logins` to the value 3

max_logins = 3

# Assign `login_attempts` to a specific value

login_attempts = 4

# Determine whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed,
# and display the resulting Boolean value

print(login_attempts <= max_logins)

False

To assign a specific value to login_attempts, I wrote the value to the right of the = operator.

## Question 7

Based on the different values you assigned to login_attempts, what did you observe about the output?

The Boolean value in the output changes depending on the value assigned to login_attempts. As an example, when login_attempts is assigned to 4, the output is False, which indicates that login_attempts is not less than or equal to max_logins. In other words, the current number of log in attempts the user has made has exceeded the maximum number of attempts allowed.

## Task 10

In this task, I'll create a variable called login_status, which is a Boolean that represents whether a user is logged in. Assign False to this variable and store its data type in a variable called login_status_type and display it.
I replaced each ### YOUR CODE HERE ### with my own code before running the following cell.

# Assign `login_status` to the Boolean value False

login_status = False

# Assign `login_status_type` to the data type of `login_status`

login_status_type = type(login_status)

# Display `login_status_type`

print(login_status_type)

<class 'bool'>

To assign the Boolean value False to the login_status variable,  I wrote False to the right of the = operator.
 
## Question 8

Based on the output above, what do you observe about the data type of login_status?

The output shows that the data type of the login_status is bool, which means that login_status stores a Boolean value.

## Conclusion

What are your key takeaways from this lab?
-	The = assignment operator allows the analyst to assign or reassign a specific value to a variable.
-	The <= comparison operator allows you to compare the value of one variable to the value of another.
-	The type() function in Python helps you to determine the data type of an object.
-	If you pass in a variable to type(), it will output the data type of the value stored in the variable.
-	The print() function in Python allows you to display information.
-	It can take in a value directly, a variable that stores a value, or a comparison between variables that evaluates to a Boolean value.

<img width="468" height="639" alt="image" src="https://github.com/user-attachments/assets/bee323db-1ddd-49ec-9798-faca9a41fe41" />
