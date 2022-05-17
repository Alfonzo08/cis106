---
Name: Alfonzo J. Irrizarri
Class: CIS106
Semester: Spring 2022
---

# List of Commands
<hr>
 
 # date

## Description
print or set the system date and time.
## Syntax
`date`
## Example
* Description of example: print the system date and time
  * `date`

<hr>

# uname
## Description
print system information
## Syntax
`uname + options`
## Example
* Description of example: print system information
  * `uname`


<hr>
    
# du
## Description
estimate file space usage.
## Syntax
`du+ options + files`
## Example
* Description of example: estimate file space and human-redable in Downloads.
  * `du -ha ~/Downloads`
* Description of example: estimate file space and human-redable in Music
  * `du -ha ~/Music`
* Description of example: estimate file space and human-redable in Pictures
  * `du -ha ~/Pictures`

<hr>
    
# free
## Description
Display amount of free and used memory in the system
## Syntax
`cmd + free`
## Example
* Description of example: Display amount of free and used memory in the system
  * `free`

<hr>
    
# echo
## Description
display a line of text
## Syntax
`echo + "String"`
## Example
* Description of example: Display "Hello World"
  * `echo "Hello World"`

<hr>

 # apt
## Description
command-line interface
## Syntax
`sudo+ apt + install + Package Name`
## Example
* Description of example: Install serveral Program in a single command
  * `sudo apt install firefox flameshot caffeine -y`
* Description of example: remove several program in a single command
  * `sudo apt remove firefox flameshot caffeine -y`
* Description of example:install and remove software in a single command
  * `sudo apt install firefox+ flameshot- caffeine- vlc+ -y`
  
<hr>  

# pwd
## Description
used for displaying your current working directory
## Syntax
`pwd`
## Example
* Description of example: displaying your current working directory.
  * `pwd`

<hr>
    
# cd
## Description
Use to change current working directory
## Syntax
`cd + Destination`
## Example
* Description of example: move from Home directory to Downloads folder.
  * `cd ~/Downloads`
* Description of example: move from Home directory to Music.
  * `cd ~/Music`
* Description of example: move from Home directory to Pictures.
  * `cd ~/Pictures`

<hr> 

# ls
## Description
used to display all files inside a give directory
## Syntax
`ls + file/directory`
## Example
* Description of example: this will show all the files in the folder Downloads.
  * `ls ~/Downloads`
* Description of example: this will show all the files in the folder Music.
  * `ls ~/Music`
* Description of example: this will show all the files in the folder Picture.
  * `ls ~/Pictures`

<hr>
    
# tree
## Description
list contents of directories in a tree-like format.
## Syntax
`tree + options`
## Example
* Description of example: list all the contents of directories Downloads.
  * `tree ~/Downloads`
* Description of example: list all the contents of directories Muisc.
  * `tree ~/Music`
* Description of example: list all the contents of directories Pictures.
  * `tree ~/Pictures`

 <hr>

# man
## Description
an interface to the system reference manuals
## Syntax
`man + options`
## Example
* Description of example: ls command manuals
  * `man ls`
* Description of example: cp command manuals
  * `man cp`
* Description of example:tree command manuals
  * `man tree`

<hr>
    
# mkdir
## Description
make directories
## Syntax
`mkdir + the name of the Directory`
## Example
* Description of example: Create a directory in the present working directory.
  * `mkdir wallpapers`
* Description of example: Create multiple directories.
  * `mkdir wallpapers/cars wallpapers/cities wallpapers/forest`
* Description of example: Create a directory with parent directory at the same time.
  * `mkdir -p wallpapers_others/movies`

 <hr>

# touch
## Description
is used for creating files.
## Syntax
`touch + options`
## Example
* Description of example: To create a file called list
  * `touch list`
* Description of example: To create several files:
  * `touch cars.txt script.py names.csv`
* Description of example: To create a file using absolute path:
  * `touch ~/Downloads/games.txt`

 <hr>

# rm
## Description
removes files
## Syntax
`remove + options`
## Example
* Description of example: Remove a file
  * `rm list`
* Description of example: Remove a file and prompt confirmation before removal
  * `rm -i list`
* Description of example: Remove anempty directory.
  * `rmdir Downloads/games`

 <hr>

# cp
## Description
copies files/directories from a source to a destination
## Syntax
`cp + file to copy + destination`
## Example
* Description of example: To copy a file
  * `cp Downloads/wallpapers.zip Pictures/`
* Description of example: TO copy a directory with absolute path
  * `cp -r ~/Downloads/wallpapers ~/Pictures/`
* Description of example: to copy multiple files in a single command
  * `sudo cp-r script.sh program.py home.html assets/ /var/www/html/`

<hr>
    
# mv
## Description
moves and renames directories.
## Syntax
`mv + source + destination`
## Example
* Description of example: to move a file from a directory to another using relative path
  * `mv Downloads/homework.pdf Documents/`
* Description of example: to move multiple directories/files to a different directory
  * `mv games/wallpapers/rockmusic/ /media/student/flashdrive/`
* Description of example: to rename a file
  * `mv homework.docx cis106homework.docx`

<hr>
    
# stat
## Description
Enter description here
## Syntax
`stat [OPTION]... FILE...`
## Example
* Description of example: to view the file details of a file residing in the current home directory, execute:
  * `stat file1.txt`
* Description of example: You can view a detailed report on multiple files by specifying the files on the command line one after the other as shown:
  * `stat file1.txt file2.pdf`
* Description of example: For more command options , use the –help option with stat command as shown.
  * `stat --help`

<hr>
    
# Wildcards (*,?,[])
## Description
Represent letters and characters used to specify a file name for searches.
## Syntax
`cmd + options`
## Example
* Description of example: will match all files that end in .txt
  * `ls *.txt`
* Description of example: To match all files that have a vowel after letter f:
  * `ls f[aeiou]*`
* Description of example: to match all files whose name has at least one number.
  * `ls *[!0-9].*`

<hr>
    
# Brace expansion
## Description
is not a wildcard but another feature of bash that allows you to generate arbitrary strings to use with commands.
## Syntax
`cmd + options`
## Example
* Description of example: To create directory structure in a single command:
  * `mkdir -p music{jazz,rock}/{mp3files,vidoes,oggfiles}/new{1..3}`
* Description of example: To create a N number of files use:
  * `touch website{1..5}.html`
* Description of example: Remove multiple files in a single directory
  * `rm -r {dir1,dir2,dir3,file.txt,file.py}`

<hr>
    
# cat
## Description
is used for displaying the content of a file.
## Syntax
`cat + option + file to display`
## Example
* Description of example: Display the content of a file using absolute path
  * `cat ~/Documents/todo.md`
* Description of example: Display the content of a file with line numbers
  * `cat -n ~/Documents/Todo.md`
* Description of example: Display the content of a file with line numbers excluding empty line
  * `cat -b ~/Documents/todo.md`

<hr>
    
# head
## Description
Display the top N number of lines of a given file.
## Syntax
`head + option + files`
## Example
* Description of example: Display the first 10 line of a file.
  * `head -10 ~/Documents/Book/dracula.txt`
* Description of example: Display the first 5 lines of a file
  * `head -5 ~/Documents/Book/dracula.txt`
* Description of example:Display the first 100 line of a file.
  * `head -100 ~/Documents/Book/dracula.txt`

<hr>
    
# tail
## Description
Display the last N Number of line of a given file.
## Syntax
`tail + option + file`
## Example
* Description of example: Display the last 10 line of a file.
  * `tail -10 ~/Documents/Book/dracula.txt`
* Description of example: Display the last 5 line of a file.
  * `tail -5 ~/Documents/Book/dracula.txt`
* Description of example: Display the last 100 line of a file.
  * `tail -100 ~/Documents/Book/dracula.txt`

 <hr>

# cut
## Description
is used to extract a specific section of each line of a file and display it to the screen.
## Syntax
`cut + options + files`
## Example
* Description of example: Display a list of all the users in your system
  * `cut -d ':' -f1 /etc/passwd`
* Description of example:Display a list of all the users in your system with their login shell
  * `cut -d ':' -f1,7 /etc/passwd`
* Description of example: Cut a range of bytes per line
  * `cut -b 1-5 usernames.txt`

<hr>

# tr
## Description
is used for translating or deleting characters from standard output.
## Syntax
`Standard output | tr + option + set + set`
## Example
* Description of example: Translate one character to another
  * `cat file.txt | tr '.' ','`
* Description of example: Translate white space into tabs.
  * `cat program.py | tr "[:space:]" '\t'`
* Description of example:Translate tab into space.
  * `cat file.py | tr "[:space:]" ' '`

<hr>
    
# paste
## Description
is used for joining files horizontally in columns
## Syntax
`paste + option + files`
## Example
* Description of example: Merge two files
  * `paste users.lst ip_address.lst`
* Description of example: Merge two files using a different delimiter
  * `paste -d ":" user1.lst ip_addresses.lst`

<hr>
    
# wc

## Description
is used for printing the number of lines,characters and bytes in a file.
## Syntax
`wc + option + files`
## Example
* Description of example: Display the number of characters in a file
  * `wc -m users.txt`
* Description of example: Display the number of line in a file
  * `wc users.txt`
* Description of example: Display the number words in a file
  * `wc -w users.txt`

<hr>
    
# grep

## Description
is used to search text in given file. it works line by line basis.
## Syntax
`grep + options + search criteria + files`
## Example
* Description of example: Search any line that contains the word "dracula" in the given file:
  * `grep 'dracula ~/Documents/dracula.txt`  
* Description of example: Search any line that contains the word "dracula" regardless of the case in the given file:
  * `grep -i 'dracula ~/Documents/dracula.txt`
* Description of example: Search and display only the matched string
  * `grep -o 'dracula ~/Documents/dracula.txt`

 <hr>

# output redirection

## Description
redirect the input and output of commands to and from files as well as connecting multiple commands together into powerful command pipelines.
## Syntax
`command_1 | command_2 | command_3 | .....| command_N`
## Example
* Description of example:Use grep to look for a string in a particular man page
  * `man ls | grep "human-readable"`
* Description of example: Display only the 2nd line in a file
  * `head -2 file.lst | tail -1`

<hr>
    
# Saving the output of a command

## Description

## Syntax
`command output + > + file`
## Example
* Description of example: Save the output of a command to a file
  * `ls -lA ~ > all-files-in-home.txt`
* Description of example: Save the error generated by a command to a file
  * `ls -lA downloads/ 2> error-of-ls`
* Description of example: Do not Display errors. send errors to the black hole
  * `ls -lA downloads/ 2> /dev/null`

<hr>
    
# vim or nano (basic stuff: open a file, close a file, edit a file)

## Description
On Unix-like operating systems, vim, which stands for "Vi Improved", is a text editor. It can be used for editing any kind of text and is especially suited for editing computer programs.
## Syntax
`cmd + vim`
## Example
* Description of example: Start vim with a file name
  * `vim food.txt`
* Description of example: save the file
  * `press esc key,type:w`
* Description of example:Exit vim
  * `press esc, type:q`

 <hr>

# tar

## Description
Creates archives by combining files and directories into a single file.
## Syntax
`tar + options + archive name + file to add to archive`
## Example
* Description of example: Create archive
  * `tar -cf example.tar file1 file2 file3`
* Description of example:extract archive
  * `tar -xf example.tar`
* Description of example:Extract archive in a different directory
  * `tar -xf example.tar --directory ~/Downloads`

<hr>
    
# gz, bzip2, or xz

## Description
gz, bzip2, xz - compress or expand files
## Syntax
`Compression utility-option<path of compressed file> file with the same name without extension`
## Example
* Description of example:Display a file that has been compressed with bzip2
  * `bzcat file.bz2`
* Description of example:Compress a single file
  * `gzip file.txt`
* Description of example: Compress multiple files
  * `gzip file1.txt file2.txt file3.txt`

 <hr>

# chmod

## Description
change file permission on files
## Syntax
`chmod permissions file/directory`
## Example
* Description of example: Give execute permission to use.
  * `chmod u+x script.sh`
* Description of example: Remove (other) execute permissions 
  * `chmod o-x script.sh`
* Description of example: assing multiple permission to user,other and group.
  * `chmod u=rwx,g=rw,o=r script.sh`