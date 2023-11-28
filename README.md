# Member Registration Application

## Overview

The Member Registration Application is a Python GUI program built with tkinter and openpyxl that allows you to easily add member information to an Excel spreadsheet. It provides a user-friendly interface for entering member details and automatically updates the spreadsheet with the data.

## Features

- User-friendly graphical user interface (GUI).
- Organized form with different sections for member details.
- Automatic generation of unique sheet names in the Excel workbook.
- Seamless integration with Excel for data storage and retrieval.
- Ability to view the date of member registration.

## Requirements

- Python 3.x
- tkinter (typically included with Python)
- openpyxl library (`pip install openpyxl`)

## Usage

1. Clone or download the project repository to your local machine.

2. Install the required libraries if you haven't already:

   ```bash
   pip install openpyxl

```bash
# Run the member_registration.py script:

python member_registration.py

# The main application window will open, featuring an "Add Member" button. Click this button to open the member registration form.

# Fill out the member registration form with the required information. The form is organized into sections for general, contact, residential, employment, and nominee information.

# After filling out the form, click the "Add Member" button to add the member to the Excel spreadsheet. A confirmation message will be displayed.

# You can close the program using the "Close" button.

# Excel Spreadsheet

The program uses an Excel spreadsheet named "Registration_Book.xlsx" to store member data.

Each member's data is added to a separate sheet with a unique name (e.g., MG001, MG002, etc.).

The "Member_List" sheet maintains a list of registered members, including their names, ID/passport numbers, and registration dates.


# Customization

You can customize the structure of the member registration form by modifying the fields list in the AddMemberForm class.

Additional fields or sections can be added as needed.

You can also customize the appearance of the GUI, such as window size and button text.


# Author

- Purity Anne

# Acknowledgments

Special thanks to the open-source community for the tkinter and openpyxl libraries.
