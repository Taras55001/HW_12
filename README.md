# Contact Book with Birthday Reminder and Text-to-Speech

This Python script, `phone_parser.py`, extends the functionality of a contact book by adding a birthday reminder and incorporating text-to-speech capability. You can add, change, delete, and display contact records with phone numbers and birthdays. Additionally, the script can find contacts by name or phone number and provide information about the days remaining until a contact's birthday.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/Taras55001/HW_12.git
    cd HW_12
    ```

2. Run the script:

    ```bash
    python phone_parser.py
    ```

3. Follow the on-screen instructions to interact with the contact book, birthday reminder, and text-to-speech functionality.

## Commands

- `'add name phone_number birthday'` - Adds a new contact with the specified name, phone number, and birthday.
- `'change name old_phone_number new_phone_number'` - Changes the phone number for a contact.
- `'birthday name'` - Displays the days remaining until a contact's birthday.
- `'delete name'` - Deletes a contact by name.
- `'find search_query'` - Finds a contact by name or phone number.
- `'show'` - Shows the list of contacts with their phone numbers and birthdays.
- `'good', 'bye', 'close', 'exit'` - Exits the script.

## Text-to-Speech

The script utilizes the `pyttsx3` library to convert text output into speech. Make sure you have the necessary dependencies installed.

## Example

Here is an example of using the script:

```bash
--------------------------------------------------
Input command 
(example: 'add name phone_number birthday'): add John 123456789876 10-02-1990
Contact John created successfully
--------------------------------------------------
Input command 
(example: 'add name phone_number birthday'): show
John: +123456789876, birthday 10-02-1990
--------------------------------------------------
```

Feel free to modify and integrate this script into your projects.

Replace `123456789` and other placeholder values with actual data if needed.
This `README.md` file provides a basic overview of the script and instructions for using it.


## Author

Taras55001
