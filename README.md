# Quiz Application

This is a command-line quiz application built with Python. It features user registration, login, and quiz attempts with score tracking and high-score functionality. User and score data are saved persistently to files.

---

## Features

- **User Registration**: New users can create accounts.
- **User Login**: Existing users can log in securely.
- **User Deletion**: Admin can delete user accounts.
- **Quizzes**: Users can attempt quizzes on:
  - Python
  - Data Structures and Algorithms (DSA)
  - Computer Science Essentials (CSE)
- **Score Tracking**:
  - Tracks the highest scores for each user and quiz.
  - Updates the high score only when a new score exceeds the previous one.
- **Persistent Storage**:
  - User credentials stored in `users.txt`.
  - Quiz scores stored in `scores.txt`.

---

## Requirements

- Python 3.6 or higher
- File permissions for creating and writing to `users.txt` and `scores.txt`.

---

## File Structure

- **`users.txt`**: Stores user credentials in the format:
username,password
- **`scores.txt`**: Tracks scores in the format:
username,quiz_type,score


---

## How to Run

1. Clone or download the project to your local system.
2. Open a terminal and navigate to the folder containing the program.
3. Run the program using:
 ```bash
 python quiz_app.py
```

Example Usage
# Register

Main Menu
1. Register
2. Login
3. Delete User
4. Exit
Enter your choice (1-4): 1

Register
Enter username: ansh
Enter password: password123
Registration successful! Please login to continue.

# Login and Attempt Quiz
Main Menu
1. Register
2. Login
3. Delete User
4. Exit
Enter your choice (1-4): 2

Login
Enter username: ansh
Enter password: password123
Login successful!

Quiz Menu
1. Attempt Quiz
2. View High Scores
3. Logout
Enter your choice (1-3): 1

Select a quiz:
1. Python
2. DSA
3. CSE
Enter your choice (1-3): 1

What is the output of print(len('Hello'))?
1. 4
2. 5
3. 6
4. 7
Your answer: 2

Which function is used to get input from a user in Python?
1. get()
2. input()
3. read()
4. scan()
Your answer: 2

Quiz completed! Your score: 2/2
Your highest score in python quiz: 2

# View High Scores
Quiz Menu
1. Attempt Quiz
2. View High Scores
3. Logout
Enter your choice (1-3): 2

High Scores for ansh:
python: 2
