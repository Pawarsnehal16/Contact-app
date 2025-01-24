# Contact-app
This Contact-app is a Python-based program that allows users to manage a list of contacts stored in a text file. Users can add, delete, update, search, and view contacts, making it a simple and efficient tool for contact management.

## Features
### View Contacts:

Displays all the contacts stored in the contacts.txt file.
### Add Contact:

Adds a new contact to the file. Each contact consists of:
Name
Email
Phone number
### Delete Contact:

Removes a contact by specifying the contact name.
### Update Contact:

Updates a contact's details (name, email, or phone number) by specifying the contact name.
### Search Contact:

Searches for a specific contact by name and displays the matching contact details.
### Quit Program:

Ends the program execution.
## How to Use
Run the script in a Python environment.
Follow the prompts to perform desired actions:
Press 'a': Add a new contact.
Press 'o': Open a contact (view, update, or delete).
Press 's': Search for a specific contact by name.
Press 'q': Quit the program.
## File Structure
The contacts are stored in a file named contacts.txt.
Each contact is stored on a separate line in the format:
  name, email, phone_number
## Error Handling
Invalid input for search, update, or delete actions is managed gracefully.
Duplicate or invalid numbers are flagged when adding contacts.
Ensures that the file remains updated even if the program encounters errors.
## Future Enhancements
Add a feature to validate email and phone number formats.
Include a graphical user interface (GUI).
Implement sorting or filtering of contacts.
Encrypt the contact data for security.
