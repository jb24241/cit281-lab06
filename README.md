# CIT281 Lab 6

## Overview

Lab goals and outcomes:

1. Join GitHub and work through Introduction to GitHub course.
2. Create lab file.
3. Classes overview.
4. Create and test Book class.
5. Create and test Library class.
6. Add at least two more books to the library.
7. Add ISBN and a delete book method.

## Deliverables

- `lab-06.js`

These files should be placed in your `cit281/p5` folder and zipped into `lab-06.zip`.

## Instructions

### Part 1: Join GitHub and work through Introduction to GitHub course

1. Go to the [GitHub Sign up page](https://github.com/join) and join GitHub.
2. Once you've joined GitHub, navigate to the [GitHub Skills](https://skills.github.com/) page.
3. Click on "Start with Introduction to GitHub" and proceed through the course.

### Part 2: Create lab file

1. Create a new file named `lab-06.js` in the `cit281/p5/lab-06` folder.

### Part 3: Classes overview

1. Create a `Book` class according to the following specification:

   ```javascript
   class Book {
     constructor(title, author, pubDate, isbn) {
       this.title = title;
       this.author = author;
       this.pubDate = pubDate;
       this.isbn = isbn;
     }
   }
