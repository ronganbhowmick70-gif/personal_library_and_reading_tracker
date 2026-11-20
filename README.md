Personal Library & Reading Tracker
A Python-based command-line application designed to manage a personal book collection and track reading progress. The application allows users to organize books, monitor their reading status, update progress, search their collection, and view reading statistics.

This project demonstrates practical implementation of Python programming concepts, Object-Oriented Programming (OOP), modular application architecture, JSON-based data persistence, exception handling, and clean coding practices.

📌 Project Overview
The Personal Library & Reading Tracker provides a simple and efficient way to maintain a digital record of your personal book collection.

Users can add new books, view and search their collection, update reading progress, mark books as finished, and monitor their reading habits through statistics.

The application uses JSON for data storage, ensuring that book information and reading progress are preserved even after the program is closed.

The project is developed using a modular Python structure to maintain readability, scalability, reusability, and maintainability.

✨ Features
1. Book Management
Add new books with title, author, genre, and total pages.

View all books in the collection.

Remove books from the collection.

Search books by title or author.

Support partial and case-insensitive searches.

2. Reading Progress Tracking
Maintain three reading statuses:

To-Read

Reading

Finished

Update the current reading page.

Track reading progress for books currently being read.

Automatically record the finish date when a book is marked as finished.

3. Book Filtering
Filter books based on their reading status.

Filter books based on genre.

Easily organize and navigate through the collection.

4. Reading Statistics
View useful insights about your reading habits, including:

Total number of books in the collection.

Number of books finished during the current year.

Average pages read per finished book.

Most-read (favorite) genre.

5. Data Persistence
Store book information in a JSON file.

Automatically load previously saved data when the application starts.

Preserve the book collection between multiple application sessions.

6. Error Handling
Custom exceptions for handling application-specific errors.

Handle invalid user inputs gracefully.

Prevent unexpected application crashes through appropriate exception handling.

🛠️ Technologies & Concepts Used
Technology / Concept	Purpose
Python 3	Core programming language
Object-Oriented Programming	Classes, objects, encapsulation, inheritance, and composition
JSON	Data storage and persistence
Exception Handling	Managing runtime errors and invalid inputs
Custom Exceptions	Handling application-specific errors
Type Hinting	Improving code readability and maintainability
Docstrings	Documenting modules, classes, and methods
Modular Programming	Organizing code into reusable modules
Git & GitHub	Version control and project management
Virtual Environment	Isolating project dependencies
📂 Project Structure
The project follows a modular architecture to separate data models, business logic, storage operations, and user interaction.

personal_library_and_reading_tracker/
│
├── src/
│   ├── __init__.py
│   ├── models.py          # Book model and custom exceptions
│   ├── library.py         # Library management and business logic
│   ├── storage.py         # JSON data storage and retrieval
│   └── cli.py             # Command-line interface
│
├── main.py                # Application entry point
├── data.json              # Persistent book storage (created as needed)
├── requirements.txt       # Project dependencies
├── README.md              # Project documentation
└── .gitignore             # Files excluded from version control
Module Description
File	Responsibility
models.py	Defines the Book class, book attributes, reading status, and custom exceptions.
library.py	Handles book management operations, reading progress, searching, filtering, and statistics.
storage.py	Manages saving and loading book data using JSON.
cli.py	Provides the user-facing command-line menu and handles user interactions.
main.py	Acts as the main entry point and starts the application.
⚙️ Installation & Setup
Follow these steps to run the project on your local machine.

Prerequisites
Make sure you have the following installed:

Python 3.10 or above

Git

A terminal or command-line interface

Step 1: Clone the Repository
git clone <your-repository-url>
Navigate to the project directory:

cd personal_library_and_reading_tracker
Step 2: Create a Virtual Environment
Create an isolated Python environment:

For macOS / Linux:

python3 -m venv venv
For Windows:

python -m venv venv
Step 3: Activate the Virtual Environment
For macOS / Linux:

source venv/bin/activate
For Windows (Command Prompt):

venv\Scripts\activate
For Windows (PowerShell):

.\venv\Scripts\Activate.ps1
Step 4: Install Dependencies
Install the required dependencies:

pip install -r requirements.txt
If the project uses only Python's standard library, no additional third-party packages are required.

Step 5: Run the Application
Start the application using:

python main.py
The command-line interface will display the application menu, allowing you to manage your personal book collection.

▶️ How to Use
After running the application, follow the menu instructions to perform the available operations.

The application supports the following operations:

Add a Book

View All Books

Update Reading Progress

Mark a Book as Finished

Remove a Book

Search Books

Filter Books by Status or Genre

View Reading Statistics

Exit

Note: The exact menu options depend on the implemented CLI.

💾 Data Storage
The application uses JSON (JavaScript Object Notation) to store book information.

The collection is saved in data.json, allowing the application to retrieve previously stored information whenever it is launched again.

This ensures that users do not lose their book collection or reading progress after closing the application.

🎯 Learning Objectives
This project was developed to strengthen practical Python programming skills through the implementation of a real-world application.

Key learning outcomes include:

Understanding and implementing Object-Oriented Programming principles.

Building a modular, multi-file Python application.

Working with classes, objects, and custom exceptions.

Implementing JSON-based file handling and data persistence.

Applying error handling using try, except, else, and finally.

Writing clean, readable, and maintainable Python code.

Using type hints and docstrings.

Following PEP 8 coding conventions.

Managing dependencies using virtual environments.

Applying Git and GitHub for version control.

🚀 Future Enhancements
The application can be extended with additional functionality, such as:

Exporting the book collection into CSV or Markdown reports.

Adding a 1–5 star rating system.

Adding personal notes and book reviews.

Implementing application logging.

Packaging the application for installation using pip install -e ..

Adding automated unit tests and improving test coverage.

🔧 Version Control
Git is used to maintain the project's development history and track changes.

To initialize Git:

git init
To stage and commit changes:

git add .
git commit -m "Initial project setup"
To connect the GitHub repository:

git remote add origin <your-repository-url>
git branch -M main
git push -u origin main
👨‍💻 Author
Sayan Maity

Python Developer | Data Enthusiast

📄 License
This project is developed for educational purposes and practical implementation of Python programming concepts.