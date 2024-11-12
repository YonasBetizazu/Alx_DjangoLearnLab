# Update Operation

This document describes how to update an existing book instance in the database.

## Command:
To update the title of the book from "1984" to "Nineteen Eighty-Four", we can use the following commands in the Django shell:

```python
# Retrieve the book instance
retrieved_book = Book.objects.get(title="1984")

# Update the title
retrieved_book.title = "Nineteen Eighty-Four"
retrieved_book.save()



### Instructions for Use
- Make sure to save the file after adding the content.
- Ensure that the code blocks are properly formatted with triple backticks (```) to maintain Markdown formatting.

### Verify the Creation
- After saving the file, you can verify that it exists by running:
  ```bash
  ls LibraryProject/bookshelf/
