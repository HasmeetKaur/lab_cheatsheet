# Cheatsheet 
## Created 09/08/22

This is a cheet sheet containing some popular commands.

## Terminology
**Terminal** is the terminal
**Shell** is the screen
**Oh-My-Zsh** makes the twirly lines in the terminal

# Terminal Commands ##
- **open .** opens the folder to find things
- **pwd** Print work directory - to find which folder your currently in
- **list** Lists all the visible contents of the directory
- **ls -l** The flag l gives a list of files and folders along with permissions, owner and date last modified
Note: it's important to put the space
- **ls -al** Gives all the files and folders (.name) in the directory, including hidden configuration/system ones
- **clear** Clears from screen but you can scroll up
- **man** Short for manual, can tell you what you do with command
- **man ls**
- **q** Press q to come out
**Warning:** Dont delete anything with a dot- they are hidden files from tools like finder

## File Navigation ## 
- **cd** Change directory - e.g. cd Documents, can use tab to find the next folder
- **cd** or **cd ~** to go back to the home directory
- **cd -** to go back to the previous directory

- **mkdir** Makes a directory
**Note** Use distinct names
**Note** Use . at the beginning of the name making it a hidden folder
- **touch my_file.xml** touch, creates a new file
**Note:** Try not to use spaces. Html: use dashes. JS: underscore.
**Note:** Deleting from the terminal - means its gone
- **rm another_file** deletes not moves to trash, is like cut and paste
- **mv** for move - This one needs two pieces of information: the thing we're moving and the place we're moving it to
eg. mv my_picture.png .. The .. shortcut means "the directory above this one" and we can use it from anywhere in the system. A single dot . means "this directory".
- **mv picture.png ..** moves it up a level
- **Mv picture.png profile_photo.png** renames files. Can rename and move a file at the same time
- **cp** Copy. cp profile_photo.png my_directory. Copy and remove give errors when you do it on a directory
- **cp -r** can rename and copy a file
- **rm** remove a file
- **rm -r** used to remove a folder - recursive - does it over and over 
No need to mv and can do ls-r
Can do multiple directores
Note: Sometimes we will be asked for confirmation before deleting something, usually if something else might depend on it being there. We can bypass this confirmation by adding the -f flag, but only do this if you are absolutely certain that you want to be deleting the folder!

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
