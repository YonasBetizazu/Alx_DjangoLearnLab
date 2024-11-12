# Delete Operation

This document describes how to delete an existing book instance from the database.

## Command:
To delete the book we created earlier, we can use the following command in the Django shell:

```python
# Retrieve the book instance
retrieved_book = Book.objects.get(title="Nineteen Eighty-Four")

# Delete the book instance
retrieved_book.delete()



### Instructions for Use
- Make sure to save the file after adding the content.
- Ensure that the code blocks are properly formatted with triple backticks (```) to maintain Markdown formatting.

### Verify the Creation
- After saving the file, you can verify that it exists by running:
  ```bash
  ls LibraryProject/bookshelf/
