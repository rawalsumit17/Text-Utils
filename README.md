TextUtils

TextUtils is a web application built with React and Vite, designed to perform various text manipulation tasks. The app allows users to easily switch between light and dark modes, convert text to uppercase or lowercase, copy text, clear text, remove extra spaces, and calculate the average reading time for a paragraph.

Features
Mode Toggle: Switch between light mode and dark mode with a single click.
Text Conversion: Convert text between uppercase and lowercase.
Copy Text: Copy the current text to the clipboard.
Clear Text: Clear the text area with a single button click.
Remove Extra Spaces: Remove any extra spaces from the text.
Reading Time: Calculate the estimated reading time for the given text.
Technologies Used
React: A JavaScript library for building user interfaces.
Vite: A build tool that provides fast development and optimized production builds.
Bootstrap: A popular CSS framework used for styling the components.
Installation
To get started with TextUtils, follow these steps:

1. Clone the Repository
   bash
   Copy code
   git clone https://github.com/rawalsumit17/Text-Utils.git
2. Navigate to the Project Directory
   bash
   Copy code
   cd text-utils
3. Install Dependencies
   Ensure you have Node.js installed. Then run:

bash
Copy code
npm install 4. Start the Development Server
bash
Copy code
npm run dev
Open your browser and navigate to http://localhost:3000 (or the port specified) to view the application in action.

Usage
Light/Dark Mode
Toggle between light and dark modes using the switch in the navbar. The background color and text color will adjust according to the selected mode.
Text Conversion
Convert to Uppercase/Lowercase: Use the provided buttons to switch the text between uppercase and lowercase.
Copy Text: Click the "Copy Text" button to copy the current text to the clipboard.
Clear Text: Click the "Clear Text" button to remove all text from the textarea.
Remove Extra Spaces: Click the "Remove Extra Spaces" button to trim any extra spaces from the text.
Reading Time
The estimated reading time is calculated based on the number of words in the text and is displayed below the text area.
Example Usage
jsx
Copy code
<TextForm
  heading="TextUtils - Word Counter, Character Counter, Remove Extra Spaces"
  mode={mode}
  showAlert={showAlert}
/>
Contributing
If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.

Acknowledgements
React - For building user interfaces.
Vite - For fast build and development.
Bootstrap - For styling and responsive design.
