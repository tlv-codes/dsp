# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > * show current working directory path = pwd
> > * creating a directory = mkdir
> > * deleting a directory = rmdir *directory name*
> > * creating a file using `touch` = touch *file name*
> > * deleting a file = rm *file name*
> > * renaming a file = mv *old file name* *new file name*
> > * listing hidden files = ls -d
> > * copying a file from one directory to another = cp -av *source directory path* *destination directory path*
---
> > * return to default directory = cd ~
> > * run last command = up-arrow-key
---

### Q2.  List Files in Unix   

What do the following commands do:  
* `ls` 
* `ls -a` 
* `ls -l` 
* `ls -lh` 
* `ls -lah`  
* `ls -t`  
* `ls -Glp`  

> > * `ls` = listing of directory contents
> > * `ls -a` = listing of all contents, including hidden files
> > * `ls -l` = long listing of directory contents
> > * `ls -lh` = long listing of directory contents with human readable file sizes
> > * `ls -lah` long listing of directory contents with human readable, including hidden files
> > * `ls -t` = list directory contents, sorted by modification time
> > * `ls -Glp` =  long listing of directory contents with both color-coded file types and icon indicator of file type

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > * `ls -r` = displays files in reverse order
> > * `ls -R` = displays subdirectories as well
> > * `ls -u` = displays file by their access time
> > * `ls -1` = displays each entry on a line
> > * `ls -F` = displays file names

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > 'xargs' allows you to create a script that iterates over basic input.    
> > the below will create three files, named first, second, and third, in whatever directory the command is run from:
      
      example:   
      print echo 'first' 'second' 'third' | xargs touch 

 


 

