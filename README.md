# Assignment #2: Greatreads!

<img width="410" height="200" align="right" src="https://user-images.githubusercontent.com/110256838/201998232-ca739984-4cff-4eb8-87f8-431068ac49e0.png">

[Goodreads](https://www.goodreads.com/) is a website that allows users to rate, review, and interact with books. Users can add books to their "bookshelves" ("to-be-read pile"), rate and leave reviews on books, and browse books and their reviews on the site. For this assignment, your task  is to implement some of the features of this site, using an Object-Oriented approach.

Your complete solution will consist of 4 classes: Book.java, Reviews.java, Shelf.java, and the driver class, Main.java. 

## Main.java 
- Will contain only a main method and create Book, Reviews, and Shelf objects and display them. 
- Your code should be able to do the following:
  - Create Book objects and print out the data of the object in a neatly formatted way (Book Title, Author, Summary, and Page Count)
  - Create Reviews objects for Books, both text and a rating (assume scale of 1-5). Print out the text reviews for a type of Book, add a new text review for a Book, add a rating for a type of Book, and display the average rating.
  - Create a new book Shelf and add Books to each Book shelf, and display the shelf(s).

[Refer to the diagrams](https://docs.google.com/document/d/1hvafOBSbA3AwGaEmhiK_PsIh2FsOlzujWYBmacnC5Rg/edit?usp=sharing) below for the class variables and methods.

<img width="316" alt="image" src="https://user-images.githubusercontent.com/110256838/201993593-5a374b47-43ab-4578-b0a8-af9f531f3d44.png">

<img width="315" alt="image" src="https://user-images.githubusercontent.com/110256838/201995184-becc2336-71f4-4f69-be17-54db7e68477e.png">

<img width="316" alt="image" src="https://user-images.githubusercontent.com/110256838/201993690-9beb2f74-9c89-45dd-bdcb-8f9b998d7055.png">

The implementation of each class is up to you, but must adhere to these diagrams. Meaning, all class variables and methods must be present in order to have a completely working solution. You may not change the return type of any methods.

You are also expected to have good Code Documentation as part of your solution. This includes proper indentation, whitespace, comments, and variable naming conventions.

**NOTE**: You may not import any additional packages or libraries.

## Example Code output

### Displaying Books:
```
Title of book: The Lightning Thief
Written by: Rick Riordan
Summary: The Lightning Thief is a light-hearted fantasy about a modern 12-year-old boy who learns that his true father is Poseidon, the Greek god of the sea.
Page Count: 377
Title of book: To Kill a Mockingbird
Written by: Harper Lee
Summary: To Kill a Mockingbird is both a young girl's coming-of-age story and a darker drama about the roots and consequences of racism and prejudice, probing how good and evil can coexist within a single community or individual.
Page Count: 281
```
### Displaying a Shelf contents:
```
Shelf: To Be Read
The Lightning Thief
To Kill a Mockingbird
```
### Displaying Average Reviews:
```
The Lightning Thief Reviews: 2.75
To Kill a Mockingbird Reviews: 1.5
```

### Displaying Reviews for To Kill a Mockingbird:
```
This book was boring
This book was good!
```

## Marking Scheme
The marking scheme for this assignment is follows:

#### Knowledge
  - Appropriate use of variables, conditionals, loops, and methods
  - Variable data types are accurately defined
#### Thinking
  - No unnecessary or unused variables, conditionals, loops, etc.
#### Application
  - All program specifications have been met.
  - Use of Object-Oriented Programming in the approach to the solution
  - Working solution; program does not generate any errors (syntax/compiler, logic errors, etc.)
  - Code deliverable is submitted on time or by pre-arranged extension date.
#### Communication
  - Code is well-documented with comments
  - Variable names are clear and concise 

### Total Marks: /20
