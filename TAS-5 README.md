This Java code implements a basic Library Management System where an admin can add, view, and delete books, and a user can browse through the available books. The code is structured with three main classes: Book, Admin, and User, along with the LibraryManagementSystem class to execute the application.

Class Breakdown:

1. Book Class:

Represents a book with two attributes: title and author.

The toString() method is overridden to provide a readable string representation of a book.



2. Admin Class:

Manages the list of books in the library using an ArrayList<Book>.

Methods:

addBook(String title, String author): Adds a new book to the collection.

viewBooks(): Displays all the books currently in the collection. If no books are available, it informs the user.

deleteBook(String title): Removes a book based on the title.




3. User Class:

Allows a user to browse the books.

The browseBooks() method calls the viewBooks() method from the Admin class to display available books.



4. LibraryManagementSystem Class:

Contains the main method that acts as the entry point of the program.

Uses a menu-based system with the following options:

Admin can add a book, view all books, or delete a book.

A user can browse available books.

The program runs in a loop until the user selects the "Exit" option.


The program uses a Scanner for input and switches between different functionalities based on the user's choice.




Program Flow:

The admin can add books by providing a title and author.

Admin can view or delete books.

The user can browse books added by the admin.

The program continues to run until the user chooses to exit by selecting option 5.
