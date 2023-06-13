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







