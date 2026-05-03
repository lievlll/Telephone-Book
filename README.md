# Telephone-Book
## Author
Anfalova Yana

## Description
Console-based Phone Book application using Python OOP and MVC architecture.  
Supports adding, deleting, searching, filtering contacts and saving/loading data in JSON format.

## Features

- Add contact

- Delete contact

- Search by name

- Search by phone

- Filter contacts

- Undo last action (stack-based)

- Save to JSON file

- Load from JSON file

## Architecture

- MVC pattern:

  - Model: Contact

  - View: ConsoleView

  - Controller: PhoneBookController

- Services:

  - FileService (JSON handling)

  - HistoryService (Undo stack)

## How to run
python main.py
