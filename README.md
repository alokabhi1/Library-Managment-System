# Library-Managment-System
The Library Management System is a Java application for managing books in a library. It allows users to add, issue, return, and view available books. Books are stored in an array, and issued books are marked as null. The system tracks the number of books and provides a simple interface for library operations.
it is a console based project.


**Features**

**Add Books:** The system allows adding books to the library collection. Each book is stored in an array, and the total number of books is tracked.

**Show Available Books:** Displays the list of all books that are currently available in the library. Issued books are not displayed in the available list.

**Issue Books:** Users can issue books from the library. Once issued, the book is removed from the available list, and it is marked as null in the array.

**Return Books:** Users can return books they have issued, and the book is re-added to the available books list.

**Structure**
**Library Class:** The core class that handles book operations like adding, issuing, returning, and showing books.

**addBook(String book):** Adds a new book to the library collection.

**showAvailableBooks():** Displays all the books available in the library.

**issueBook(String book):** Issues a book by removing it from the available list.

**returnBook(String book):** Allows a book to be returned and added back to the collection.

**ONLINE_LIBRARY_MANAGEMENT Class:** This class contains the main() method where a library object is created and various methods are invoked to demonstrate the system’s functionalities.
