#!/bin/bash
echo Hello, World prints “Hello, World”, followed by a new line to the standard output
echo \"\(Ôo\)\' displays a confused smiley "(Ôo)'
cat /etc/passwd display the content of the /etc/passwd file
cat /etc/passwd /etc/hosts display the content of /etc/passwd and /etc/hosts
tail -n 10 /etc/passwd display the last 10 lines of /etc/passwd
head -n 10 /etc/passwd display the first 10 lines of /etc/passwd
head -n 3 iacta | tail -n 1 write a script that displays the third line of the file iacta
echo Best School | cat > \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) writes a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line
ls -la > ls_cwd_content writes a script that writes into the file ls_cwd_content the result of the command ls -la
tail -n 1 iacta | cat >> iacta writes a script that duplicates the last line of the file iacta
find . -name "*.js" -type f -delete Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
ls -lt | head Displays the 10 newest files in the current directory
sort | uniq -u Creates a script that takes a list of words as input and prints only words that appear exactly once.
grep root /etc/passwd display lines containing the pattern “root” from the file /etc/passwd
grep -c bin /etc/passwd Display the number of lines that contain the pattern “bin” in the file /etc/passwd
cat /etc/passwd | grep -A 3 "root" Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
greo -v bin /etc/passwd Display all the lines in the file /etc/passwd that do not contain the pattern “bin”
grep ^[[:alpha:]] /etc/ssh/sshd_config Display all lines of the file /etc/ssh/sshd_config starting with a letter
tr 'Ac' 'Ze' Replace all characters A and c from input to Z and e respectively
tr -d 'Cc' Create a script that removes all letters c and C from input
rev Write a script that reverse its input
cut -d":" --fields=1,6 /etc/passwd | sort Write a script that displays all users and their home directories, sorted by users.
find . -empty -printf "%f\n" Write a command that finds all empty files and directories in the current directory and all sub-directories
find . -type f -name "*.gif" -printf "%f\n"| rev | cut -d '.' -f2- | rev | LC_ALL=C sort -f Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories
echo -ne $(cut -c-1 | tr -d '\n')'\n' Create a script that decodes acrostics that use the first letter of each line
tail -n +2 | cut -f1 | sort | uniq -c | sort -nr -k 1,1 | cut -c 9- | head -11 Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests








