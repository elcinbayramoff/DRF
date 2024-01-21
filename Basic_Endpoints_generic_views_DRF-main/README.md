# Creating simple APIs in DRF, generic views, and etc

In this project, /api/books and /api/books/id are created. Using generic views, we created 2 classes in views.py and the first is inherited from CreateList, while the second from RetrieveUpdate. So, accordingly the first view is for /api/books where we can create a field for Book model, and see the list of books, and the second is for /api/books/id. Writing id of the book we can get according book(retrieve) and we can update values of it. More can be used but for this project only 2 of them are present.

