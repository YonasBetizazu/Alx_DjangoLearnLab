# CRUD Operations on Book Model

This document outlines the Create, Retrieve, Update, and Delete operations performed on the `Book` model in the `bookshelf` app.

## Create Operation

To create a new book instance in the database, we will use the Django ORM in the Django shell.

### Command:

```python
from bookshelf.models import Book

# Create a new book instance
book = Book(title="1984", author="George Orwell", publication_year=1949)
book.save()
```
