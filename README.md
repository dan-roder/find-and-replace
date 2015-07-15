# fandr
Find and Replace in files script

## Installation Notes

Make sure to add the script to your $PATH so you can run the 'fandr' command from anywhere. There are a number of ways to accomplish this. The simplest is to add the script to the folder `/usr/local/bin`. A more correct way would be to have a bin in your user space as described [here](http://apple.stackexchange.com/questions/99788/os-x-create-a-personal-bin-directory-bin-and-run-scripts-without-specifyin).

## Usage Instructions

The script takes 3 arguments

1. Path in which you want to search i.e. ~/Documents/folder/
2. What you're looking for i.e. someonesemail@domain.com
3. What you want to replace it with i.e. newemail@newdomain.com

Full example using info above:
fandr ~/Documents/folder someonesemail@domain.com newemail@newdomain.com

The script will run a grep command first and print the results of a search first and then prompt you if you want to run the replace.  This will allow you to just use the script to find something if you'd like.

Expected inputs
y - Run the find and replace
n - Exit

Any unexpected input will exit the script

I will probably enhance this eventually but wanted to get one working quickly
