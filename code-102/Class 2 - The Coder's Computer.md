# Class 02 Notes - The Coder's Computer

## Command Line

Description: a text based interface where a user can enters commands to interact with the system

Process of using command line in terminal
1. system presents prompt
2. user enters command

  - command (tells the computer what to do), command line argument (modify behavior of command and typically start with a -)
  - terminal runs command and displays results if available
3. system presents prompt 

## Basic Navigation

PWD: print working directory

ls: list contents in current directory

-  ls -l: long listing includes notation for normal file (-) or director (d) and metadeta
-  ls /etc: list directory contents
-  ls -l /etc: long listing of directory contents

Paths describe the means to a particular file or directory in a system

- Absolute path: specify a location in relation to root directory (identified by /)
- Relative paths specify a location
- ~: home directory
- .: reference to current directory (where I currently am)
- ..: reference to parent directory (go back one directory)

CD: change directory

## Additional Files Details

- Linux does not use the extensions to determine file type
- Linux is case sensitive
- Linux is picky with spaces
- \: escape character denotes to nullify the special meaning of the next character 
  - ex. cd Holiday\ Photos --> creates directory called Holiday Photos
- ls -a list contents, include hidden files

## Answer
What are four important features to look for in a text editor?
1. compatibility accross multiple operating systems
2. syntax highlighting
3. customizable themes
4. code completion shortcuts

What do the following commands do?

1. pwd (print working directory) states the current directory terminal is working in
2. ls - lists all the contents within that directory
3. cd - change directory (used to move to another directory)
4. mkdir - make directory (creates new directory)
5. touch - make a file (file needs to include .filetype)

Can you explain what is happening in the following scenario if these commands and arguments are entered into the command line? (Arguments are extra instructions given to a command.)

1. cd projects - changes the current directory to the directory named projects
2. mkdir new-project - creates a new directory called new-project
3. touch new-project/newfile.md - creates a markdown file named newfile within the new-project folder
4. cd .. - goes back two directories
5. ls projects/new-project - lists all the contents within the projects/new-project folder


