# Create Operation

To create a new book instance in the database, we will use the Django ORM in the Django shell.

## Command:

```python
from bookshelf.models import Book

# Create a new book instance using the create method
book = Book.objects.create(title="1984", author="George Orwell", publication_year=1949)
```
