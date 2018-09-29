# Ruby Lesson 1: Basic Variables, List Operations

## Initial Setup

Create a file in this directory called `lesson1.rb`. Place all code for this lesson in `lesson1.rb`. Each exercise will build on the previous. Make sure to keep all steps shown in your code file as separate lines.

## Variables and Printing

1. Create an array of names called `names`. It should contain the following names in this order: `John Doe`, `Sally Banana`, `Zamir Cool`, `Bob Awesome`.
1. Using Ruby's built-in `sortBy` method, sort the names in ascending order.
1. Now write some code to sort the names in descending order.
1. Write code to print out the results of steps (2) (3).

## Hashes

Now that you've gotten a list of names printing to the console, let's make that list more interesting and useful. You'll be using hashes here.

Make a list of hashes called `people`. it should contain the same people above, but this time make sure the hash structures the names into `first_name` and `last_name`. Also, add `job_title` to the hash for each person, just like this:

```
Id  Name          Job Title
1   John Doe      Software Engineer
2   Sally Banana  Chemist
3   Zamir Cool    Chemist
4   Bob Awesome   Mechanic
```

1. Write code to sort the list of hashes by last name alphabetically.
1. Write code to sort the list of hashes by job title alphabetically.
1. Write code to find chemists in the list, sort them by last name alphabetically, then print each name on a separate line, with last name then first name. The console output should look like this:

```
Banana, Sally
Cool, Zamir
```

Congratulations! You've just learned demonstrated your knowledge about how to store data, search through it, and print out the formatted results! Great job!
