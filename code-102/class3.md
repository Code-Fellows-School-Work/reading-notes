# Class 3 Notes - Revisions and the Cloud

## Revisions and the Cloud

### Vocab words

<b>Version control</b> - system that stores versions of code in order to revisit previous recordings and track modifications. Benefit of version control allows to fix mistakes by reverting back to old working code

<b>Local vs centralized</b> version control - version control system (VCS) stored locally vs version control system stored online. Benefit of centralized version control is to allow multiple developers to collaborate writing code without having to be locally present

<b>Distributed version control</b> - advanced version of centralized VCS with a backup redundancy feature to mitigate risk of lost or corrupted code

## Purpose of Git

Commonly used DVCS to store code and allows multiple developers to collaborate0

Git local operations meaning??

Tracks changes and detects file corruption

Git states:
  1. Commited - data is securely stored in local database
  2. Modified - file has been changed but not committed to the database
  3. Staged - flagged a file's changed version to be commited in the next snapshot

Git allows use of graphical user interface (GUI) tools or third-party tools allowing for customization of user experience

Git workflow components
  1. Working directory - actual files reside here
  2. Index - area used for staging
  3. Head - points to the most recent commit

Saving changes states - all files in a check out (or working) copy of a project file
  1. Tracked - these files can be modified, unmodified or staged; they were part of the most recent file snapshot
  2. Untracked - files not in last snapshot and do not current reside in the staging area

Life cycle of file status
  1. You edit a file --> Git flags as modified because of changes after it's previous commit
  2. You stage the modified file
  3. You request commit staged changes

### Tracking and staging a new file

git add filename - track one file
git add * track all files in repository
git commit -m "made changes x,y,z" - commmit changes and adds coding commets
git commit -a - commits a snapshot of all modifications to tracked files in working directory
git push origin master (pushes changes from local "master" branch to remote repository named "origin"
git stash - save changes without committing

## Answer
  1. What is Version Control? - system that stores code and allows user to revist old code for reference or to restore broken code
  2. What is cloning in Git? - creates copy of an exisiting Git repository 
  3. What is the command to track and stage files? git add filename or git add *
  4. What is the command to take a snapshot of your changed files? git commit -m ""
  5. What is the command to send your changed files to Github? git push origin main
