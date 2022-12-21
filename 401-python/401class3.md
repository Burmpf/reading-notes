# FIleIO and Exceptions

### SOURCES
#### VIDEOS
[Read & Write Files in Python - Companion Video]()
[]()
[]()

#### ARTICLES
[Read & Write Files in Python](https://realpython.com/read-write-files-python/)
[Exceptions in Python]()
[]()

## NOTES

#### *Read & Write Files in Python*
- to use a file in python you must first use the built in function opne() to open it.
- one way to close a file is a try-finally block (similar to try catch from js)
- another way to close a file is using a with statement. A with statement automatically closes a file when it leaves the with block
- you can also use characters in addition, like "r" which means read-only
- you can use functions like reader.readline() to read files and .write() to write to files
  
#### *Exceptions in Python*
- Syntax errors appear when the user inputs code incorrectly
- a exception error is when code is written in a way that isnt "wrong" but also doesnt work. 
- python so far seems to give much better and more clear error messages
- 
- "raise allows you to throw an exception at any time.
- assert enables you to verify if a certain condition is met and throw an exception if it isn’t.
- In the try clause, all statements are executed until an exception is encountered.
- except is used to catch and handle the exception(s) that are encountered in the try clause.
- else lets you code sections that should run only when no exceptions are encountered in the try clause.
- finally enables you to execute sections of code that should always run, with or without any previously encountered exceptions."