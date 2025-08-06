# 🔹About create new python file

---

## What is .py or .md or .html etc?
- `.py` is a file extension for Python scripts.
- `.md` is a file extension for Markdown files.
- `.html` is a file extension for HTML documents.
## How to create a new file in Python?
- You can create a new file in Python using the built-in `open()` function with the `'w'` mode (write mode). Here's an example:
```python
# Create a new file named 'example.py'
with open('example.py', 'w') as file:
    file.write('# This is a new Python file\n')
```