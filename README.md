# Password Manager


This simple password manager application is built using the Tkinter library in Python. It allows users to generate strong passwords and store them along with associated website details in a JSON file.

## Features
### Password Generator
- Clicking the "Generate Password" button will create a random password with a mix of letters, numbers, and symbols.
### Save Password
- Enter website details (website, email/username, password) and click the "Add" button to save the information securely in a JSON file named "myfile.json."
### Search Password
- Enter a website in the search field and click the "Search" button to retrieve stored login information for that specific website.
## How to Use
### Generate Password:

- Click the "Generate Password" button to create a random password.
- The generated password is displayed in the "Password" entry field and automatically copied to the clipboard.
### Save Password:

- Enter the website, email/username, and password.
- Click the "Add" button to save the information.
- If the JSON file "myfile.json" doesn't exist, it will be created.
### Search Password:

- Enter the website in the search field.
- Click the "Search" button to retrieve and display the saved email/username and password for that website.
- If the website is not saved, an error message will be displayed.
## Note
- Ensure the "logo.png" file is in the same directory as the script for the logo to be displayed.
- The saved data is stored in a JSON file named "myfile.json."
## Dependencies
- Tkinter (standard library)
- pyperclip (for copying generated passwords to the clipboard)
- json (standard library)
