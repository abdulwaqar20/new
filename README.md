# Book Recommendation System

#### Video Demo: <URL HERE>
#### Description:
The **Book Recommendation System** is a Python-based command-line application that helps users discover books based on their preferences. Users can add books to a database, search for books by genre, author, or keyword, view all books in the database, and delete books they no longer need. This project is designed to be simple yet functional, making it easy for users to manage and explore a collection of books.

---

## **Features**
1. **Add a Book**: Users can add a new book to the database by providing the title, author, genre, and description.
2. **Recommend Books**: Users can search for books based on their preferences (e.g., genre, author, or keyword).
3. **View All Books**: Users can view a list of all books in the database.
4. **Delete a Book**: Users can delete a book from the database by specifying its title.

---

## **Files**
1. **`project.py`**: The main script containing the logic for adding, recommending, viewing, and deleting books. It includes the following functions:
   - `add_book(title, author, genre, description)`: Adds a book to the database.
   - `recommend_books(preference)`: Recommends books based on user preferences.
   - `view_all_books()`: Displays all books in the database.
   - `delete_book(title)`: Deletes a book from the database.
   - `display_books(books)`: Helper function to display a list of books.

2. **`books.csv`**: A CSV file that serves as the database for storing book information. Each book entry includes:
   - Title
   - Author
   - Genre
   - Description

3. **`test_project.py`**: A test file containing unit tests for the custom functions in `project.py`. It includes the following test cases:
   - `test_add_book()`: Tests the `add_book` function.
   - `test_recommend_books()`: Tests the `recommend_books` function.
   - `test_view_all_books()`: Tests the `view_all_books` function.
   - `test_delete_book()`: Tests the `delete_book` function.

4. **`README.md`**: This file, which provides an overview of the project, its features, and instructions for use.

---

## **How to Use**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/waqar20/book-recommendation-system.git
   cd book-recommendation-system
