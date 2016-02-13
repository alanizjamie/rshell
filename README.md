# rshell
CS100 Assignment 2
# Introduction 
This program runs as a bash terminal. It functions with the same commands as a standard bash terminal and uses perror() to give feedback on the execution of command.
My parter and I had many problems with github mostly with committing to eachothers githubs (it kept saying permission denied). So I pulled from his, and then  we commited to our own githubs and then attempted to merge at the end. That is why it may appear that there was only one contributor. We are attempting to fix this.
Update: It would appear we have fixed the problem.
#Install Instructions
To install this project:
```
$ git clone https://github.com/alanizjamie/rshell.git
$ cd rshell
$ git checkout hw1
$ make
$ bin/rshell
```
#Known Bugs/Limitations
* Tabs, control + character, and arrow keys are treated as characters and not auto-finish.
* cd .. does not work while stringed together with another command via a connector.
* The command "wait" produces an error
* Using cd with a comment produces an error but not the same error as a standard shell
* The || connector does not work with certain commands missing their arguments (i.e. "ls-" or "mkdir")  
