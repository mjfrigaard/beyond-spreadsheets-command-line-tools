Beyond Spreadsheets : command line tools for managing data
=================

![](images/01-cli.png)

This is a repository for some basic command line skills for processing and managing data. 

The tutorial is [here](https://github.com/mjfrigaard/bu-beyond-spreadsheets/blob/master/doc/bu-beyond-spreadsheets.md) or you can follow the links to the slides below.

## Topics covered

`echo` - outputs text as arguments, prints to Terminal screen, file, or in a pipeline

`pwd` - print working directory   
`cd` - change directories    
`whoami` - user/login info   
`ls` - list all files  
`head` - print top of file   
`tail` - print bottom of file

`mkdir` - create directory  
`touch` - create a few files  


`ls -la` - list all files, including hidden ones   
`rmdir` - remove a directory  (*EXTRA*)   
`cat` - display a text file in Terminal screen  (*EXTRA*)   

`grep` - globally search a regular expression and print   

`>> and > `- redirect output of program to a file (don’t display on Terminal screen)

`curl` - download stuff from the INTERNET

`sudo` and `sudo -s` (BE CAREFUL!!) performing commands as root user can carry some heavy consequences. (*EXTRA*)

## Slides 

The slide deck for this presentation is [here](http://bit.ly/33DuKMt)

Comment on the slides [here](http://bit.ly/bu-beyond-spreadsheets)

## RStudio.Cloud project 

There is an RStudio cloud project with the `docs/bu-beyond-spreadsheets.md` file [here](https://rstudio.cloud/project/618815)

## Set up 

This repo: 

https://github.com/mjfrigaard/bu-beyond-spreadsheets

These commands:

```sh
% git init 
% git add -A 
% git commit -m "first commit"
% # sync with github 
% git remote add origin https://github.com/mjfrigaard/bu-beyond-spreadsheets.git
% git push -u origin master 
```