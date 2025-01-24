# Contact_app_regex
This repository contains a Python-based Contact_app that allows users to add, view, update, and delete contacts. The application includes input validation using regular expressions to ensure that all user data is valid before being stored.

## Features
### Add Contact

Users can add a new contact with the following fields:
Name (only alphabets and spaces allowed).
Email (validated using standard email regex).
Phone Number (exactly 10 digits, no alphabets allowed).
Date of Birth (DOB in YYYY-MM-DD format with valid date and month ranges).
Invalid input will prompt an error message and prevent saving the contact.
### View Contacts

Displays all saved contacts in the system.
### Update Contact

Update an existing contact's name, email, or phone number with validation.
### Delete Contact

Delete a specific contact by name.
### Search Contact

Search for a contact by name.
### Open Contact

Perform update or delete operations for a specific contact.
## How to Run
### Clone the repository:
  git clone <repository-url>
  cd <repository-folder>
Make sure you have Python 3 installed on your system.

### Run the script:
  python contact_management.py
Interact with the application using the following commands:

a: Add a new contact.
o: Open a contact for update or delete operations.
s: Search for a contact.
q: Quit the application.
## Input Validation
Name: Only alphabets and spaces are allowed.
Email: Must follow the pattern <text>@<domain>.<extension>.
Phone Number: Must be exactly 10 digits.
DOB: Must follow YYYY-MM-DD format, ensuring the day and month are valid.
## Validation Logic
The system uses the following regular expressions:

Name: [a-zA-Z\s]+
Email: \w+@\w+\.[a-z]{2,3}
Phone Number: \d{10}
DOB: (19|20)\d{2}-(0[1-9]|1[0-2])-(0[1-9]|[12]\d|3[01])
## File Structure
contacts.txt: Stores all contact information in the format:
  Name, Email, Phone Number, DOB
contact_management.py: Main script for managing the application.
