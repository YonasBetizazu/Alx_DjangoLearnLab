# Delete Operation

This document describes how to delete an existing book instance from the database.

## Command:
To delete the book we created earlier, we can use the following command in the Django shell. First, we need to import the `Book` model:

```python
from bookshelf.models import Book

# Retrieve the book instance
retrieved_book = Book.objects.get(title="Nineteen Eighty-Four")

# Delete the book instance
retrieved_book.delete()

Book.objects.all()
QuerySet []



### Instructions for Use
- Make sure to save the file after adding the content.
- Ensure that the code blocks are properly formatted with triple backticks (```) to maintain Markdown formatting.

### Verify the Update
- After saving the file, you can verify that it contains the correct information by checking its content:
  ```bash
  cat LibraryProject/bookshelf/delete.md
