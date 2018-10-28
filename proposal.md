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

Create a system to manage a libray's book inventory. We should be able to look up a book by ISBN number, add new books, remove books, and check books out. This information could be stored in hash table. The table will also keep track of the number of books in stock. In Main.java we can load the data structure from disk, and enter into the GUI part of the program.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
Library Managment Software


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
Number of copies availible, a brief summary of it, the author, the location of it, the genre, and page count.


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
ISBN number of a book. An adminstrator will enter the books and its information into the hash table which a customer will then be able to see. Search by book title, author's name. (To be implemented later)


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
A search bar at the top. In the middle, the top line of text can be the book title, then on the next line the book's author, below that a brief summary of the book.


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
BookNode - holds information about the number of copies, the number of in stock copies, the author, the summary, the books location, and the ISBN.
Main - loads the data structure from disk, and enters the GUI
Button - an object that we can attach various actions to.
TextField - an object that the user can enter textual information. (Search bar, book entry, etc.)
Window - an object that will hold the other graphical compnents and other state information like what mode the program is in (Admin or Customer), and the table containing the inventory of books.


Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

