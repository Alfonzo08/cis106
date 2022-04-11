---
Name : Alfonzo J. Irrizarri
Class : Cis106
Semester : Spring 2022
---




# Homework 6

## Wildcards

+ the main wild card is a star or asterisk (*) character.
+ use when you want to list all files with a particular file extension.
+ when you want to copy,move or remove all files that match a particular naming convention.
+ ? wildcard matches precisely one character.
+ the bracket "[]" wildcard match a single character in a range


## Brace expansion and how to use it

+ Brace expansion is not a wildcard but another feature of bash that allows you to generate arbitrary strings to use with commands.
+ you can use to create a whole directory structure in a single command. `mkdir -p music/{jazz}/`
+ to create a number of file use . `touch file {A....Z}.txt`
+ Remove multiple file in a single directories `rm -r {file1,fil2}`