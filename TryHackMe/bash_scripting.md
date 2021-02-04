# Bash Scripting

Lab Link - <https://tryhackme.com/room/bashscripting>

### Task 1: Introduction
-------------------------------
No Answer Needed!!!

### Task 2: Our first simple bash scripts
-------------------------------
What piece of code can we insert at the start of a line to comment out our code?
- *#*
> #! /bin/bash

What will the following script output to the screen, echo “BishBashBosh”
- BishBashBosh
> 'echo' is used to output text to the screen

### Task 3: Variables
-------------------------------
What would this code return?
- Jammy is 21 years old
> Because 'echo' function will output only the variables $name & $age

How would you print out the city to the screen?
- `echo $city`

How would you print out the country to the screen?
- `echo $country`

### Task 4: Parameters
-------------------------------
How can we get the number of arguments supplied to a script?
- $#

How can we get the filename of our current script(aka our first argument)?
- $0

How can we get the 4th argument supplied to the script?
- $4

If a script asks us for input how can we direct our input into a variable called ‘test’ using “read”
- read test

What will the output of “echo $1 $3” if the script was ran with “./script.sh hello hola aloha”
- hello aloha
> $1 will print the first argument i.e. hello & $3 will print third argument i.e. aloha.

### Task 5: Arrays
-------------------------------
`cars=('honda' 'audi' 'bmw' 'tesla')`

What would be the command to print audi to the screen using indexing.
- echo "${cars[1]}"

If we wanted to remove tesla from the array how would we do so?
- unset cars[3]
> 'unset' is used to delete or remove entries from arrays.

How could we insert a new value called toyota to replace tesla?
- cars[3]="toyota"

### Task 6: Conditionals
-------------------------------
What is the flag to check if we have read access to a file?
- -r

What is the flag to check to see if it's a directory?
- -d

### Task 7: Further Reading
-------------------------------
No Answer Needed!!!

## Additional Resources
Bash Scripting Cheatsheet (1) - <https://devhints.io/bash>

Bash Scripting Cheatsheet (1) - <https://github.com/LeCoupa/awesome-cheatsheets/blob/master/languages/bash.sh>
