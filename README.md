# -Command-Line-Library-Book-Manager-

Overview

This is a simple command-line application to manage a small library's book collection. It allows users to add books, list all books, search for books by title, author, or year, borrow and return books, and saves the data locally to a file so progress is saved between uses.
The project is designed to practice and demonstrate Object-Oriented Programming (OOP), file input/output (I/O), and basic command-line interface (CLI) interactions using Python.

Features

Add new books with title, author, year, and ISBN.
List all books with their availability status (borrowed or available).
Search books by title, author, or year.
Borrow a book if it is available.
Return a borrowed book.
Prevent borrowing of already borrowed books.
Save and load the library data in a JSON file (books.txt) for persistence.
Menu-driven CLI with input validation for smooth user experience.

Code Structure

Book class: Represents individual books and handles borrowing/returning logic.
LibraryManager class: Manages the entire collection of books, user interactions, data saving/loading, and CLI menu.
Books are saved in books.txt in JSON format for easy readability and data persistence.

File Format

Books data is stored as a list of dictionaries in JSON format inside books.txt.
Each book entry includes:
title (string)
author (string)
year (integer)
isbn (string)
is_borrowed (boolean)
