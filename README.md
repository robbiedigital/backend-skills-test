# Backend Skills Test
In this exercise you'll create a simple REST API Server that will accept a file and manipulate the data:

Rules of the test:
- Use a Backend Framework of your choice: (Django, Flask, from scratch...)
- For your convenience we have a base install of Django and Flask pre installed in this repo.
- We run on a minimum python version of 3.6.

### REST API Server Requirements
- Create an endpoint `/api/palindrome/bulk`.
  - In the root of this repo you will see a palindromes.txt file.
  - This endpoint should accept the file, parse the values, validate the strings, and return whether or not each string is a palindrome.
- Create an endpoint `/api/palindrome/:string`.
  - this endpoint should accept a single string and return whether or not the string is a palindrome.


### Bonus Objectives
- Extra: Leverage a persistent storage mechanism to save each string that is submitted to `/api/palindrome/:string`.
- Extra: Create an endpoint `/api/palindrome/history` that will return the values of the historic API calls to `/api/palindrome/:string`
- Extra: Add unit test to your REST API server.


### Definitions:
A palindrome is a word, phrase, or sequence that reads the same backward as forward. Example: Otto.

### Notes
If you have any extra time feel free to add any extra features or improvements you would like.
