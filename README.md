# Password Generator
This is a password generator app built with React and TypeScript that allows users to create custom passwords based on their preferences. The app includes options for uppercase, lowercase, numbers, and symbols, as well as a strength rating system and the ability to copy the generated password to the clipboard.

## Features
- Customizable Password: Choose to include uppercase letters, lowercase letters, numbers, and symbols in the generated password.
- Password Length: Adjust the password length using a range input, with a minimum value based on selected options and a maximum of 20 characters.
- Password Strength Rating: The generated password is rated and color-coded based on its strength:
  - Red: Too weak
  - Orange: Weak
  - Yellow: Medium
  - Green: Strong
- Copy to Clipboard: Use the Clipboard API to quickly copy the generated password with a single click.
## Installation
To run this project locally, follow these steps:

1. Clone the repository:
`git clone https://github.com/yourusername/password-generator.git`

2. Navigate to the project directory:
`cd password-generator`

3. Install dependencies:
`npm install`

4.Start the development server:
`npm run dev`

The app will open in your browser at `http://localhost:5173` or your selected port.

## Usage
Select Password Options
- Use the checkboxes to select whether you want the password to include:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Symbols
### Adjust Password Length
- The range slider adjusts the length of the password, with a minimum value based on the number of checkboxes selected and a maximum of 20 characters.
### Generate Password
- After selecting the options and adjusting the length, click the "Generate Password" button to create a new password.
### Strength Rating
- The strength of the generated password is displayed using a color-coded system:
  - Red: Too weak
  - Orange: Weak
  - Yellow: Medium
  - Green: Strong
### Copy to Clipboard
- Once a password is generated, click the paper icon to copy it to the clipboard using the Clipboard API.
## Technologies Used
- React: For building the interactive user interface.
- TypeScript: For type safety and code maintainability.
- Clipboard API: For copying the password to the clipboard.
- Password Strength Logic: Custom algorithm to determine password strength based on the selected options.
