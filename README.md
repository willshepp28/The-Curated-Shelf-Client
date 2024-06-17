# The-Curated-Shelf

### Architecture:

The app will follow a client-server architecture, with a frontend client communicating with a backend server over HTTP(S).

### Features

- User Accounts: Support user registration, authentication.
- Book Browsing and Search: Allow users to browse and search for books by title, author, genre, or other criteria.
- Book Details: Provide detailed information about each book, including title, author, description, cover image, and availability status.
- Lending/Borrowing Management: Implement a system for users to borrow and return books, with due dates and overdue notifications.

### Data Model 
![The Curated Shelf drawio](https://github.com/willshepp28/The-Curated-Shelf-Client/assets/28759252/340b625c-6767-474b-aef0-31d3a31860ec)

### Wireframes
<img width="571" alt="Screenshot 2024-06-17 at 4 00 58 PM" src="https://github.com/willshepp28/The-Curated-Shelf-Client/assets/28759252/7301d41b-485c-4106-8da3-ef4ed552fb36">

### Endpoints 
- POST /api/register
- POST /api/login
- GET /api/books
- GET /api/categories
- GET /api/books/{book_id}
- POST /api/rent
