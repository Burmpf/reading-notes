# List Comprehension- 10k day 3

### SOURCES
#### VIDEOS
[]()
[]()
[]()

#### ARTICLES
[List Comprehensions](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python)
[]()
[]()

## NOTES
- HARD TO READ THIS ARTICLE WITH ALL THESE ADS
- AND THEN IT HAS THE AUDACITY TO CRASH
- "You can see from this example that three ingredients are necessary for a python list comprehension to work.
First is the expression we’d like to carry out. expression inside the square brackets.
Second is the object that the expression will work on. item inside the square brackets.
Finally, we need an iterable list of objects to build our new list from. list inside the square brackets."- from article
- you can use range to target items in a list
- ex. for x/2 in range(10)
- an example for letters:
  "# a list of the names of popular authors
authors = ["Ernest Hemingway","Langston Hughes","Frank Herbert","Toni Morrison",
    "Emily Dickson","Stephen King"]

 create an acronym from the first letter of the author's names
letters = [ name[0] for name in authors ]
print(letters)+"