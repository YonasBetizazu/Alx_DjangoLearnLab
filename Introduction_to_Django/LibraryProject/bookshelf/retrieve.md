# Retrieve Operation

To retrieve and display all attributes of the book we created.

## Command:
```python
retrieved_book = Book.objects.get(title="1984")
print(retrieved_book.title, retrieved_book.author, retrieved_book.publication_year)


### Instructions for Use
- Make sure to save the file after adding the content.
- Ensure that the code blocks are properly formatted with triple backticks (```) to maintain Markdown formatting.

### Verify the Creation
- After saving the file, you can verify that it exists by running:
  ```bash
  ls LibraryProject/bookshelf/
