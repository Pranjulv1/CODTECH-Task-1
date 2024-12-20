Name: PRANJUL VISHWAKARMA

Company: CODTECH IT SOLUTIONS

ID: CT08ENZ

Domain: Cyber Security

Duration: December 17, 2024 to January 17, 2025

Mentor: Neela Santhosh Kumar

Project: Password Strength Checker  
This Python project is designed to assess the strength of a user-provided password based on defined criteria. It evaluates the password's length, complexity, and uniqueness in relation to the user's username. Complexity is determined by verifying the inclusion of uppercase letters, lowercase letters, digits, and special characters. The script categorizes the password strength as "weak," "moderate," "good," or "strong" and offers constructive feedback to the user. It supports input through both interactive prompts and command-line arguments.

Specifications of the Password Strength Checker Project  
Language: Python

Functionality:

- Length Check: Confirms that the password is a minimum of 8 characters in length.  
- Complexity Check:
  - Includes at least one uppercase letter.
  - Includes at least one lowercase letter.
  - Includes at least one digit.
  - Includes at least one special character.
- Uniqueness Check: Verifies that the password does not incorporate the username or any portion thereof.  
- Strength Assessment: Classifies password strength into categories such as "weak," "moderate," "good," or "strong."  

Input Methods:

- Command Line: Accepts password and username as command-line arguments.  
- Interactive Input: Prompts the user to enter the password and username if no command-line arguments are supplied.  

Output:

- Provides feedback on the assessed password strength.  
- Identifies missing complexity criteria if the password does not meet the "strong" threshold.  

Dependencies: Standard Python libraries (e.g., re).

Usage:  
- Command Line: python password_strength_checker.py "YourPassword123!" "YourUsername"  
- Interactive: Execute the script without arguments and follow prompts to enter the password and username.  

Sample output:

![Screenshot 2024-12-20 202354](https://github.com/user-attachments/assets/4a889bc4-0142-4070-baab-75796b8d0a1a)
