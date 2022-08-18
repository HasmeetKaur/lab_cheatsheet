# Cheatsheet 
## Created 09/08/22

This is a cheet sheet containing some popular commands.

## Terminology

**Terminal** is the terminal
**Shell** is the screen
**Oh-My-Zsh** makes the twirly lines in the terminal

open . opens the folder to find things
**Terminal Commands**

- **pwd** Print work directory
- **list** Lists all the contents of the directory
- **ls -l** Gives size, name of owner, last owned
important to put the space
- **clear** Clears from screen but you can scroll up
- **man** Short for manual, can tell you what you do with command
- **man ls**
- **q** Press q to come out

**Warning:** Dont delete anything with a dot- they are hidden files from tools like finder

- **ls -al** All hidden files and all the extra info too
- **cd** Change directory - e.g. cd Documents, can use tab to find the next folder
- **mkdir** Makes a directory
**Note** Use distinct names
**Note** Use . at the beginning of the name making it a hidden folder
- **touch my_file.xml** touch, creates a new file
**Note:** Try not to use spaces. Html: use dashes. JS: underscore.
**Note:** Deleting from the terminal - means its gone
- **rm another_file** deletes not moves to trash, is like cut and paste
- **mv** for move
- **mv picture.png ..** moves it up a level
- **Mv picture.png profile_photo.png** renames files. Can rename and move a file at the same time
- **cp** Copy. cp profile_photo.png my_directory. Copy and remove give errors when you do it on a directory

- **rm -r** recursive - do sit over and over 
- **cp-r** 
No need to mv and can do ls-r
Can do multiple directores

# Git (most popular version control software)

- **.git**
- **git init**
Git allows staging changes
- **git commit -m “add facts.txt”** This comment will …..(-m means message) try not to use and
- **..** means file above - parent
- **.** means current
- **git log** Can press q takes you out
- **rm -rf.git** Takes away the git
- **:x** to exit
- **:qa! and then enter**
- **ls**      
- **git commit facts.txt -m "first commit"**
- **git config --global user.name "Your Name"**
- **git config --global user.email you@example.com**
After doing this, you may fix the identity used for this commit with:
- **git commit --amend --reset-author**
- **open facts.txt**
- **git log**
- **git revert** 
- **rm rf-git** to remove a git repository



## Commit your changes regularly as you add to your file.

## Create a repository on GitHub and link your local repository to it.

## Push your files to GitHub

## Investigate `.gitignore` files and what they are used for. Try adding one to your repository.