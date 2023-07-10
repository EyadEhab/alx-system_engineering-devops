/#!/bin/bash
#!/bin/bash

# Script to demonstrate various command-line utilities in Ubuntu

# echo command: Prints "Hello, World" followed by a new line
echo "Hello, World"

# cat command: Displays the contents of a file
cat file.txt

# head command: Displays the first few lines of a file
head file.txt

# tail command: Displays the last few lines of a file
tail file.txt

# find command: Searches for files and directories in a specified location
find /path/to/directory

# wc command: Counts the number of lines, words, and characters in a file
wc file.txt

# sort command: Sorts the lines of a file or standard input
sort file.txt

# uniq command: Filters out duplicate lines from a file or standard input
uniq file.txt

# grep command: Searches for specific patterns or regular expressions in a file
grep "pattern" file.txt

# tr command: Character-level translation or deletion
tr 'abc' 'xyz' < file.txt

# rev command: Reverses the order of characters in each line of a file
rev file.txt

# cut command: Extracts specific sections (columns) from lines of files
cut -d ',' -f 1,3 file.csv

# passwd (5): Displays the manual page for the passwd command's file format and configuration details
man 5 passwd

