#!/bin/bash
alias ls="rm *" Create a script that creates an alias Name: ls
Value: rm *
echo "hello $USER" prints hello user, where user is the current Linux user
PATH=$PATH:/action adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program
echo $PATH | tr ":" "\n" | wc -l creates a script that counts the number of directories in the PATH
printenv create a script that lists environment variables
