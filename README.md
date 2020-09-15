basic programs are based here 
/bin
the files connecting to devices such as the keyboard, mouse, and screen
/dev
configuration files
/etc
the temporary files
/tmp
the starting directory when you open a new shell, contains personal files, programs, and directories
/login directory
 a symbol shorthand for the home directory in Ubuntu and OS X
~
prints a string to the screen 
echo 
a variable that appears when the terminal is ready for a command
$
there will be several directories, one for each chapter. 
/CSB
a subdirectory in the CSB directory, the instructions for installing the software for the each chapter 
installation 
a subdirectory within the CSB directory, where we work and experiment 
/sandbox 
a subdirectory within CSB, provides all data for the examples and exercises, along with the corresponding citations for papers and websites
/data 
a subdirectory for CSB, provides solutions for the exercises, as well as sketches of the solutions in plain English. This great to use when you're stuck on a exercise 
/solutions 
opening a shell or opening the dash and type Terminal 
/Ctrl+Alt+T
this is a symbol for everything that follows is a comment. Also, use when their is multiple comments used 
/# 
reduce the amount you have to type, which in turn reduces the probability of making mistake
Tab key 
navigate the history of commands you have typed
up and down keys 
visit the beginning of the line
Ctrl+A
go to the end of the line
Ctrl+E
clear the screen
Ctrl+l
clear the line before the cursor position.
Ctrl+U
clear the line after the cursor.
Ctrl+K
kill the command that is currently running
Ctrl+C
exit the current shell.
Ctrl+D
move cursor forward one word (in OS X, Esc+F)
Alt+F
move cursor backward one word (in OS X, Esc+B).
Alt+B
modify commands 
#options -j
find the manual Unix commands 
[COMMAND]
change directory, command requires one argument to the path to the directory you want to go to 
$ cd 
move one directory up.
$ cd ..
move to the root directory.
$ cd /
move to your home directory.
$ cd ~
go back to the directory you visited previously
$ cd - 
prints your current location within the directory structure
$ pwd 
list all files and directories in the current directory 
$ ls 
list all files (as well as hidden files)
$ ls -a 
provides a log list, the number of links to a file, the user and group owning it, its size, the time and date it was changed last, and its name. 
$ ls -l 
displays file sizes in human readable units 
$ ls -lh 
navigate through the directory hierarchy. Also, used as to specify a directory. 
# absolute path and relative path 
separates the directory name in a path
# forward slash (/) in Unix, backlash (\) for Windows 
copy a file or directory, command requires two arguments: file or directory (copy) the second is: location (copy) 
$ cp 
copy a directory 
$ cp -r 
move or rename a file or directory
$ mv 
update the date of last access to the file 
$ touch 
remove a file 
$ rm 
deletes the contents of the directory recursively 
$ rm -r 
confirm the action 
$ rm -i 
make a directory 
$ mkdir 
create nested directories 
$ mkdir -p 
print file to the screen 
$ less 
jump one screen back 
CtrL+B 
concatenate and print files. Requires at least one file. 
$ cat 
line, word, and byte (character) count of a file 
$ wc 
returns the line count only 
$ wc -l 
sort the lines of a file and print the result to the screen
$ sort 
numerical sorting 
$ sort -n 
reverse the order 
$ sort -r 
provides the usage to sort a delimiter-separated file by a specific column 
$ sort -k 
only the unique files are seen, the contents should be sorted first 
$ uniq 
observe the type of file 
$ file 
print the head of a file 
$ head 
provides the number of lines to print 
$ head -n 
print the tail of a file 
$ tail 
controls the number of lines to print 
$ tail -n 
show the differences between two files 
$ diff 
informs the shell to take the output on the left of the pipe and use the input for the command 
(|)
the main Unix command to master for comma-, space-, tab-, or character 
| cut 
when data is separated by semicolons, the first line is piped onto the file to cut to specify the delimiter.
-d ";"
specify the delimiter, the second column is extracted and the first line is skipped 
| tail -n +2  
substitute or remove a specific character in a text file 
| tr 
bracketed expressions that provide a prefined set of characters 
| tr [:lower:]/ [:upper:]
use quotes to specify the space character, the backslash is a metacharacter, which signals the following character shouldn't be interpreted but represents a special code that refers to a character that is hard to represent 
\t
sort the data that's in the sixth column 
-k 6 
a wildcard; a special symbol that work as placeholderd for one or more character. This wildcard stand for zero or more characters with the exception of a leading dot 
(*)
a placeholder for any character, it has a exception of a leading dot 
(?) 
a powerful command that finds all the ines of a file that match a pattern 
grep 
count the lines that contain a match 
$ grep -c 
match only full words in grep 
$ grep -w 
make the search case insensitive 
$ grep -i 
print the two lines before or after the match 
$ grep -B 2 / grep -A 2 
show the number of line number of the match in grep 
$ grep -n 
print all lines that do not match a given pattern 
| grep -v 
recursive search 
$ grep -r 
command-line program to locate files 
$ find 
read 
(r)
write 
(w)
execute 
(x)
do nothing 
(-)
read, write, and execute file 
(rwx)
group can read and execute 
(r-x)
can only read 
(r--)
substitute user do. The system requests a password and granted administrator rights 
sudo 
open a file with the default text editor 
$ open 
repeat task with slight variation, useful to perform an identical task on multiple files or different input arguments for the same command.
$ for loop
only use wildcards for this command 
* .fasta 
what to do with the variable 
do 
resolve the location of a program 
$path
line feed 
(\r\n) 
list the last commands you executed
history
time the execution of a command 
$ time [COMMAND]
download the web page at 
$ wget [URL]
synchronize files locally ore remotely 
$ rsync 
(un)compress and package files and directories 
$tar and zip 
powerful command line text editors for much more complex text manipulation than tr
$ awk and sed 
greater sign 
(>)


