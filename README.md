A simple RESTful API for managing a collection of books using the Gin framework in Golang. Here's a brief overview of the functionality:

    book struct: Defines the structure of a book with fields for ID, Title, Author, and Quantity.
    books variable: A slice that holds a list of book records.
    getBooks function: Returns a list of all books in JSON format.
    bookById function: Retrieves a specific book by its ID and returns it in JSON format.
    checkoutBook function: Reduces the quantity of a book by 1, representing the checkout process.
    returnBook function: Increases the quantity of a book by 1, representing the return process.
    getBookById function: Helper function to find a book by ID.
    createBook function: Adds a new book to the collection.
    main function: Sets up the HTTP routes and starts the server.