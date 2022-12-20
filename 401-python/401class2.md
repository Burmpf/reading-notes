# Testing and Modules

### SOURCES
#### VIDEOS
[What on Earth is Recursion](https://www.youtube.com/watch?v=Mv9NEXX1VHc)

[Python Modules and Packages Companion Video](https://realpython.com/courses/python-modules-packages/)
[]()

#### ARTICLES
[In Tests We Trust - TDD with Python](https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932)

[If name equals main](https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/)

[Intro to Recursion](https://www.geeksforgeeks.org/introduction-to-recursion-data-structure-and-algorithm-tutorials/)

## NOTES

#### *In Tests We Trust*
- A common structure convention is AAA- Arrange, Act, Assert
  - Arrange- organize the data needed to execute the input
  - Act- this is where the code is executed
  - Assert- after running the code, check to see if the output is the expected result
- Writing a test first can make writing the bulk of the code simpler because you write it to PASS the test

#### *If name equals main*
- I have no idea what this article is saying. 
- from the article: "Before executing code, Python interpreter reads source file and define few special variables/global variables. 
If the python interpreter is running that module (the source file) as the main program, it sets the special __name__ variable to have a value “__main__”. If this file is being imported from another module, __name__ will be set to the module’s name. Module’s name is available as value to __name__ global variable. 
A module is a file containing Python definitions and statements. The file name is the module name with the suffix .py appended. "

#### *What on Earth is Recursion*
- Genuinely no idea what this is. The dude just said factoral 1 million times like im supposed to know what that even is. 
- Recursion is, in the simplest terms I can think of it, as mulitplying a number by every positive number counting down uinder it so f(6) would be 6*5*4*3*2*1=144