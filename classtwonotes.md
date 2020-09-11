# Reading notes 02

## ***The Command Line***

#### ***What are command lines?***
- A *command line*, or *terminal*, is a text based interface to the system.
- A command line presents you with a prompt as you type.

## *Example of a command line*

1. user@bash: ls -l /home/ryan
2. total 3
3. drwxr-xr-x 2 ryan users 4096 Mar 23 13:34 bin
4. drwxr-xr-x 18 ryan users 4096 Feb 17 09:12 Documents
5. drwxr-xr-x  2 ryan users 4096 May 05 17:25 public_html
6. user@bash:

## **Line 1**
- Presents us with a *prompt* ( user@bash ).
- ( *ls* ) a command that you usually input first.
- After that are command line arguments ( *-l/home/ryan* )
- ***Important Note!!! There has to be space between the command line and the first command line argument.***
- First *command line arguement* is ( *-l* ) also referred to as an option.
- Arguements typically start with a dash ( - ).

## **Lines 2 - 5**
- *Lines 2 - 5* are output from running the command.
- Most commands produce output and will be listed straight under the issuing command.
- Other commands perform their task and don't display information unless there was an error.

## **Line 6**
- *Line 6* presents us with a prompt again.
- After the command has run, it means the terminal is ready for another command.
- If no *prompt* is displayed it means the command is still running.
- ***Note to self, on your terminal there wont be any line numbers on it. This is an example to make it easier.***

## ***Opening a Terminal***
- When opening a *terminal* every system is different, but fairly easy.
#### ***Mac Os***
- Find the ***Terminal*** under ***Applications -> Utilities.***
- A short cut can be a key combination of ***command + space.***
#### ***Linux***
- Find it in ***(Applications -> System)*** or ***(Applications -> Utilities).***
- Alternative way is to *right-click* on the desktop and there will be an option *Open in terminal.*
#### ***Windows***
- For windows it should be the same as Linux.
- But if you intend to remotely log into another machine then you'll need an *SSH client.*
- A good *SSH client* is [Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) and it's also free!