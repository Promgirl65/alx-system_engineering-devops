#!/bin/bash
pwd prints the absolute path name of the current working directory
ls display the contents list of your current directory
cd ~  changes the working directory to the user’s home directory
ls -l display current directory contents in a long format
ls -al display current directory contents, including hidden files starting with dot using the long format
ls -lan display current directory contents in long format with user and group IDs displayed numerically and hidden files starting with dot
mkdir /tmp/my_first_directory creates a directory named my_first_directory in the /tmp/ directory
mv /tmp/betty /tmp/my_first_directory move the file betty from /tmp/ to /tmp/my_first_directory
rm /tmp/my_first_commit/betty delete the file betty
rm -r /tmp/my_first_commit delete the directory my_first_directory that is in the /tmp directory
cd -  changes the working directory to the previous one
ls -al . .. /boot  lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory in long format
file /tmp/iamafile prints the type of the file named iamafile and the file iamafile will be in the /tmp directory
ln -s /bin/ls __ls__ Create a symbolic link to /bin/ls named __ls__ in the current working directory
cp -un *.html ../ Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
mv [[:upper:]]* /tmp/u Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u

