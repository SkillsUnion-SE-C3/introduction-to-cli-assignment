[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Introduction to Command Line Interface: Assignment

Being a developer requires a degree of comfort navigating and interacting with your computer using the command line interface. Just as you have been practicing writing HTML, CSS, and JavaScript in the course so far, you now need to practice creating, modifying, and moving files and directories using nothing but your terminal.
## Problem

For this assignment, you're going to be creating files and directories to organize your favorite books, movies, and music.

- The setup
  - Navigate to the `~/se/assignments` directory
  - Create a new directory called `my-favorite-things`
- Organize your favorite books
  - In the `my-favorite-things` directory, create a directory called `books`
  - Create a directory in `books` named after your favorite author (e.g. `george-orwell`, or `jrr-tolkien`, but avoid spaces!)
  - Create text files named after some of the author's books in the author's directory
  - In each book file, add a brief description of the book using either:
    - Use the `echo` command to add text into the text files. _You might want to lookup how to do this._
    - If you are unable to use the `echo` command, open the `books` directory in your file explorer and edit the text files using a text editor
- Organize your favorite movies
  - In the `my-favorite-things` directory, create a directory called `movies`
  - Create a directory in `movies` named after your favorite `actor`
  - Create a directory in the `actor` directory named after the actor's breakthrough movie
  - Create a text file named after the actor's character in the breakthrough movie in the top level `movies` directory
  - Move the text file to the breakthrough movie's directory
  - Edit the text file and add a brief description of the character's role in the movie using either:
    - Use the `echo` command to add text into the text files. _You might want to lookup how to do this._
    - If you are unable to use the `echo` command,open the `movies` directory in your file explorer and edit the text files using a text editor
- Organize your favorite music
  - In the `my-favorite-things` directory, create a directory called `music`
  - Move into the `music` directory
  - Create a directory called `disco`
  - Create a text file in disco called `ymca.txt`
  - Delete the `disco` directory
  - Create a directory called `jazz`
  - In `jazz`, create directories `miles-davis` and `john-coltrane`
  - In `miles-davis`, create a directories called `kind-of-blue`
  - In `john-coltrane`, create a directory called `a-love-supreme`
  - Create a text file in both `john-coltrane` and `miles-davis` called `track-listing.txt` using one command
  - Rename both `track-listing.txt` files to be called `tracks.txt`
- Reorganize everything
  - In the `my-favorite-things` directory, create a directory called `media`
  - Move the `books`, `movies`, and `music` directories into the media directory

### Bonus Problem (Optional)

- Using research find out how to perform the following without leaving your terminal:
  - Look at the top and bottom 10 lines of each file
  - Search for a string of text in a file

## Submission Guidelines

- Cite any relevant sources consulted during your research
- Solve the problems using your own code
- Do not copy and paste solutions from the source material