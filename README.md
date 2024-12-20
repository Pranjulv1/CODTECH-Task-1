Name: PRANJUL VISHWAKARMA

Company: CODTECH IT SOLUTIONS

Id: CT08ENZ

Domain: Cyber Security

Duration:  December 17th, 2024 to January 17th, 2025

Mentor:  Neela Santhosh Kumar

Project: Password Strength Checker
This Python project evaluates the strength of a user-provided password based on specific criteria. It checks the password's length, complexity, and uniqueness relative to the user's username. The complexity assessment includes ensuring the presence of uppercase letters, lowercase letters, digits, and special characters. Based on these checks, the script categorizes the password strength as "weak," "moderate," or "strong" and provides feedback to the user. The script can take input either interactively or through command-line arguments.

Specifications of the Password Strength Checker Project
Language: Python

Functionality:

Length Check: Verifies that the password is at least 8 characters long.
Complexity Check:
Contains at least one uppercase letter.
Contains at least one lowercase letter.
Contains at least one digit.
Contains at least one special character.
Uniqueness Check: Ensures the password does not contain the username or parts of it.
Strength Assessment: Categorizes password strength as "weak," "moderate," "good," or "strong."
Input Methods:

Command Line: Accepts password and username as command-line arguments. Interactive Input: Prompts the user to enter the password and username interactively if no command-line arguments are provided. Output:

Provides feedback on the password strength. Lists missing complexity criteria if the password is not strong.

Dependencies: Standard Python libraries (re ).

Usage: Command Line: python password_strength_checker.py "YourPassword123!" "YourUsername" Interactive: Run the script without arguments and enter the password and username when prompted.
