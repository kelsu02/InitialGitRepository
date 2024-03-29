# Command Line Definitions

## cd - change directory

## ls - list directory contents

## man <command> - displays manual for given command

## mkdir <foldername> - make directory with given name

## pwd - print working directory - tells you where you are 

## touch <filename> - create file with given name

# Git Definitions

## git init - initialize an empty repository

## git add <filename> - moves a modified file to the stagining area

## git commit -m "<message>" - moves staged files to the Git Directory and labels the commit with a message for other developers

## git config --global user.name "<username>" - change or set global username

## git config --global user.email "<email>" - change or set global email address

## git config --global --list - displays your global settings

## git config --global core.editor <editor of choice> - set your global editor
 
## git commit --amend -m "<new message>" - if you forgot to add a file or you have a misspelling in your commit message. Overwrites the previous commit with new files and message

## git reset HEAD <filename> - resets head from file in staging area, basically unstages file. Moves from Staging Area to Working Directory

## git checkout -- <filename> - removes modified version of file in working directory and puts it back into previously unmodified state, basically undoes any changes you did

## git branch <branchname> - create a new branch with the given name

## git checkout <branchname> - switch to a new branch

## git checkout -b <branchname> - create new branch and switch to it - quicker way to do first two steps in one

## git branch -d <branchname> - delete existing branch with given name

## git branch - lists all of your branches and *what branch you are on

## git branch - m <oldname> <newname> - to rename branches

## git status - check stage of files and what branch you are on, check often to make sure you are where you think you are

## git log - shows you history of commits and messages

## git rebase - keeps history clean, moves history onto another branch - only use if you have been working locally not on a remote repository

## git merge <branchname> - merge the histories of two branches into one branch, creates new commit on branch merged onto 

## Merge Steps
1. git checkout <branchname of branch to be mainbranch ex:develop branch> - Checkout the branch we want to merge changes into
2. git merge <branch with changes ex:topicbranch> - pulls branch named into branch on. EX: be on develop git merge <topicbranch> to pull topicbranch into develop

