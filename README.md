# LibManagement
This is a library management application built using Django. It provides a web-based interface for managing library books, borrowers, and borrowing transactions.

## Features

- Book management: Add, update, and delete books in the library.
- Borrower management: Manage information about library borrowers.
- Borrowing transactions: Record and track borrowing transactions.
- Search functionality: Search for books by title, author, or ISBN.
- Fine calculation: Automatically calculate fines for overdue books.
- Admin interface: Secure administrative interface for managing the application.

## Prerequisites

Before running the application, make sure you have the following installed:

- Python 3.x: Install Python from the official website (https://www.python.org/downloads/).
- Django: Install Django using pip

## Installation

1. Clone the repository
2. Change into the project directory
3. Create a virtual environment
4. Activate the virtual environment:
- On macOS and Linux:
  ```
  source env/bin/activate
  ```
- On Windows:
  ```
  .\env\Scripts\activate
  ```

5. Install the project dependencies:
  - pip install -r requirements.txt
  
6. Run database migrations
7. Start the development server
8. Access the application in your browser at `http://localhost:8000`.

## Usage

- Use the admin interface to add books, borrowers, and manage borrowing transactions.
- The library homepage provides a search form to search for books.
- Borrowers can check out books by providing their information and the book details.
- The application automatically calculates fines for overdue books.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

