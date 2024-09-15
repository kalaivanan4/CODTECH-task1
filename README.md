NAME:Kalaivanan.K
COMPANY:CODTECH IT SOLUTIONS
INTERN ID: CT6WTDS408
DOMAIN:CYBER SECURITY
DURATION:AUGUST 1st, 2024 to SEPTEMBER 15th, 2024
MENTOR:Neela Santhosh Kumar 

OVERVIEW OF THE PROJECT

project:VULNERABILITY SCANNING TOOL

Purpose: The code implements a password strength assessment tool that analyzes the strength of a password entered by a user.

Key Features:

Length Analysis: Checks if the password is at least 8 characters long and rewards longer passwords with higher scores.
Complexity Analysis: Checks if the password contains a mix of uppercase and lowercase letters, numbers, and special characters.
Uniqueness Analysis: Checks if the password has been used before by hashing the password and checking against a list of previous hashes.
Feedback: Provides feedback to the user on each of the above factors and calculates an overall strength score.
Strength Score: Calculates a score based on the assessment, with higher scores indicating stronger passwords.

Implementation:

The code uses Python and defines a PasswordStrengthAssessor class.
The class has an assess_password method that takes a password as input and performs the length, complexity, and uniqueness analysis.
The method returns a strength score and a list of feedback messages.
The code uses regular expressions for complexity analysis and hashlib for hashing the password.
The get_previous_hashes method is a placeholder for implementing a mechanism to store and retrieve previous password hashes.

OUTPUT:
 ![WhatsApp Image 2024-09-15 at 6 02 30 PM](https://github.com/user-attachments/assets/9e5bfdff-cef3-4916-a156-dccb32a4c203)
