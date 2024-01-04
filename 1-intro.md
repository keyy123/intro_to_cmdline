
## Intro 

### What is the command line?

Basically, a text only way to use your computer. It will take commands to make the PC's OS run. 

### What is the pros of using commandline over a GUI?
1. Power = We can automate tasks by coding scripts,combine commands to do complex things, and run programs.


#### What are directories?
- Dictories = folders when using the command line. 

#### What is a file system?
- Filesystem = Files and dictories on your computer.

- It organizes files and folders into a [tree data structure](https://content.codecademy.com/courses/learn-command-line/img/LCL-fileTrees-01.png?_gl=1*6ynj57*_ga*MjQ1NzIyMDEwOC4xNzAzMzA4MzI5*_ga_3LRZM6TM9L*MTcwNDMyMTYyMi43LjEuMTcwNDMyMjU2Mi42MC4wLjA.)

NOTE: Commandline for programming is usually for Linux/MacOSX (unix-systems)


## ls - navigation 

- `ls` command let's us see the files and directories in the current location. 

### How to use ls command?

- In cmd, We just need to type `ls` and enter to see folders


## pwd - navigation

### What is pwd command?
- `pwd` is a command to log/show the current directory the user is in to the console as text. 

- The current directory the user is in = working directory (wd)

- Showing text to the console = printing (p)

- pwd = print the current folder the user is in to the console as text.

### Why use pwd?
1. It is useful to show where you are in the filesystem along with `ls`

### How to use `pwd`?

type `pwd` into the cmdline


## cd

`cd` = change folder (directory)

- It's how we navigate filesystem on cmdline

- If we use `..` with `cd`, we go to the parent folder from our current working directory. 

Example:

```bash
cd .. # go back up 1 directory

```

## mkdir 

Creates a new directory in the location that comes after the command. 


There are 2 ways to make a new folder:

cd into the folder you want to nest a folder in or
`cd home/ && mkdir parker`

make a folders using a relative path
`mkdir /home/parker`


RESOURCES:
- [1]:[Command Line Command](https://www.codecademy.com/articles/command-line-commands)
 
