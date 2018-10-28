# X-Team 26 Library Managment Software

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Create a system to manage a libray's book inventory. We should be able to look up a book by ISBN number, add new books, remove books, and check books out. This information could be stored in hash table. The table will also keep track of the number of books in stock. In Main.java we can load the data structure from disk, and enter into the GUI part of the program. Uses can find a book by searching by book title, author's name, ISBN.

## Questions to answer for Exercise #2

1. 
* Library Managment Software


2.  
* All information about the book which the user is looking for. 
* Number of copies available, a brief summary of it, the author, the location of it, the genre, and page count.
* Example: Unavailable, Learning a complex new language is no easy task especially when its an object-oriented computer programming language like Java. This resource combines puzzles, strong visuals, mysteries, and soul-searching interviews to offer a complete introduction to object-oriented programming and Java, Kathy Sierra, Being Relocated, Computer Science, 689


3. 
* ISBN number of a book and other relavent information (Number of copies available, a brief summary of it, the author, the location of it, the genre, and page count). An adminstrator should enter the books and its information into the hash table which a customer will then be able to see. 
* Example: 978-0201072563, 5, This book is about the creation and analysis of efficient data structures. Because many different languages approach the construction of data structures differently, we use pseudo-code so that you can translate the code into your own language, Thomas A. Standish, Space Science Library (Schwerdtfeger) Stacks QA76.9 D35 S73, Computer Science, 447


4. 
* A search bar at the top. In the middle, the top line of text can be the book title, then on the next line the book's author, below that a brief summary of the book. Before the user inputs any information, the page will display top 3 most frequent check-out books. After the user inputs any information, the page will display filtered information about the search.


5. 
* BookNode - holds information about the number of copies, the number of in stock copies, the author, the summary, the books location, and the ISBN.
* Library - hashtable based, store and check out all books
* Main - loads the data structure from disk, and enters the GUI
* Button - an object that we can attach various actions to.
* TextField - an object that the user can enter textual information. (Search bar, book entry, etc.)
* Window - an object that will hold the other graphical compnents and other state information like what mode the program is in (Admin or Customer), and the table containing the inventory of books.
* Test - to test the functionality


