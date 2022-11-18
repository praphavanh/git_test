# git_test
My 1000000000TH Github repo!
Hello Odin!


Cheatsheet

This is a reference list of the most commonly used Git commands. (You might consider bookmarking this handy page.) Try to familiarize yourself with the commands so that you can eventually remember them all:

    Commands related to a remote repository:
        git clone git@github.com:USER-NAME/REPOSITORY-NAME.git
        git push or git push origin main (Both accomplish the same goal in this context)
    Commands related to the workflow:
        git add .
        git commit -m "A message describing what you have done to make this snapshot different"
    Commands related to checking status or log history
        git status
        git log

The basic Git syntax is program | action | destination.

For example,

    git add . is read as git | add | ., where the period represents everything in the current directory;
    git commit -m "message" is read as git | commit -m | "message"; and
    git status is read as git | status | (no destination).


Changing the Git Commit Message Editor

If you are using Visual Studio Code (and you should be if you’re following this curriculum) and you don’t want to get stuck writing a commit message in Vim because you accidentally used git commit without the message flag (-m), this command will make Visual Studio Code open a new tab with the ability to write your commit message and an optional description below it: git config --global core.editor "code --wait".

There will be no confirmation or any output on the terminal after entering this command. To make a commit with Visual Studio Code as the text editor, make sure to use the git commit command without the -m flag. Just type git commit and no message after that. Once you do this, a new tab will open. Now you can write your message, and provide more information if you want, right below it. After typing your commit message, save it and exit the tab.

With that out of the way, now you can choose to use either git commit -m <your message here> or git commit and enter your message with Visual Studio Code!!

