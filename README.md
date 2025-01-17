# File Reader in Python
A simple Python script to read the contents of a file and display it on the console. This demonstrates the use of Python's open() function with a context manager for safe file handling.

## Features 
1. Efficient File Handling:
- Uses a context manager (with statement) to automatically close the file after reading.
2. Ease of Use:
- Simply place your text file in the same directory as the script and update the filename in the code.
3. Minimal Code:
- Compact and beginner-friendly implementation.

## How it works
1. The script opens a file named my_file.txt in read mode.
2. It reads the file's content using the read() method.
3. The content is printed to the console.

## Benefits of Using a Context Manager
- Automatically closes the file after reading, even if an error occurs.
- Avoids resource leaks and improves code safety.

Feel free to fork the repository and adapt the script for your needs!
