#!/bin/bash
alias ls="rm *" Create a script that creates an alias Name: ls
Value: rm *
echo "hello $USER" prints hello user, where user is the current Linux user
PATH=$PATH:/action adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program
echo $PATH | tr ":" "\n" | wc -l creates a script that counts the number of directories in the PATH
printenv create a script that lists environment variables
set creates a script that lists all local variables and environment variables, and functions
BEST="School" Create a script that creates a new local variable
export BEST="School" creates a script that creates a new global variable
echo $(($TRUEKNOWLEDGE+128)) Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line
echo $(($POWER/$DIVIDE)) writes a script that prints the result of POWER divided by DIVIDE, followed by a new line
echo $(($BREATH**$LOVE)) write a script that displays the result of BREATH to the power LOVE
echo $((2#$BINARY)) Write a script that converts a number from base 2 to base 10
