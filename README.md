# PRODIGY_CS_03

## Task-03

# Password Strength Assessment Tool

This tool assesses the strength of a user's password and provides feedback on how to improve it. It evaluates the password based on its length, use of uppercase and lowercase letters, digits, and special characters.

## Features

- **Password Strength Scoring**: 
  - Rates passwords out of 10.
  - Categories: Very Weak, Weak, Medium, Strong, and Very Strong.
  
- **Feedback**: 
  - Offers suggestions to improve the password.
  - Identifies missing elements like digits, special characters, or length.

## Compilation

### Prerequisites
Ensure that a C compiler is installed, such as `gcc` for Linux/Mac or `MinGW` for Windows.

### Compiling the Program

1. Open a terminal or command prompt.
2. Navigate to the directory with the source code.
3. Use a C compiler to compile the program.

## Usage

### Running the Program

After compiling, you can run the program from the terminal or command prompt. The program will prompt you to enter a password for assessment.

### Output

The program will display:
1. **Password Strength**: A category ranging from Very Weak to Very Strong.
2. **Detailed Feedback**: Suggestions on how to improve your password, such as adding more characters, using different types of characters, or increasing its length.

### Scoring Criteria

- **Length**: Passwords of 8 characters or more score higher, with an even higher score for 12 or more characters.
- **Character Variety**: Including lowercase and uppercase letters, digits, and special characters will improve the score.
- **Maximum Score**: A strong password with the ideal length and variety will score 10/10.

## File Structure

- **Main C source file**: Contains the logic for password strength assessment and feedback.

## License

This project is open-source and available under the MIT License.
