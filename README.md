Aim:
To study and implement the Python Dictionary data structure and perform operations such as creating dictionaries, updating values, searching records, validating user credentials, and finding maximum values using dictionary keys and values.

Theory:
A dictionary in Python is a built-in data structure that stores data in the form of key–value pairs. Each key is unique and is used to access its associated value. Dictionaries are ordered (from Python 3.7 onward), mutable, and efficient for operations such as searching, inserting, updating, and deleting data.

Unlike lists or tuples, dictionary elements are accessed using keys rather than index positions. Python offers several methods and techniques to perform operations on dictionaries, including:

Creating dictionaries using key–value pairs.

Accessing values through keys or by using the get() method.

Updating values by assigning a new value to an existing key.

Checking whether a key exists using conditional statements with the in keyword.

Using max(dictionary, key=dictionary.get) to identify the key associated with the highest value.

Dictionaries are widely applied in real-world programs such as student record systems, login authentication systems, structured data storage, and quick searching or retrieval of information.

Algorithms

Algorithm 1: Updating Value in a Dictionary

Start

Create a dictionary where items are keys and their prices or values are stored as values.

Display the original dictionary.

Select the key whose value needs to be modified.

Update the value using dictionary[key] = new_value.

Display the updated dictionary.

Stop

Algorithm 2: Student Database Using Dictionary

Start

Create a dictionary with student names as keys and their marks as values.

Input the name of the student to search.

Check whether the name exists in the dictionary using in or get().

If the name exists, display the student’s marks.

Otherwise, display “Student not found.”

Stop

Algorithm 3: Password Validation

Start

Create a dictionary containing usernames as keys and passwords as values.

Input the username from the user.

Input the password from the user.

Check whether the entered username exists in the dictionary.

If the username exists, compare the stored password with the entered password.

If both match, display “Login Successful.”

Otherwise, display “Invalid Username or Password.”

Stop

Algorithm 4: Finding the Highest Score

Start

Create a dictionary with student names as keys and their marks as values.

Use max(dictionary, key=dictionary.get) to find the student with the highest marks.

Store the name of the topper.

Display the topper’s name along with the corresponding marks.

Stop

Conclusion:
Thus, Python dictionaries were successfully studied and implemented. We learned how to create and update dictionaries, search for specific records, verify username and password credentials, and identify the highest value using dictionary operations. Dictionaries offer an efficient and flexible method for storing, organizing, and retrieving data using key–value pairs.
