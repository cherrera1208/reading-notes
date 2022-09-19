# Topics

## Command line

the command line is a text based interface to interact with the computer. Normal computer users navigate their computers through a GUI, or graphical user interface, by clicking, dragging, tapping, etc. It's the more natural way to interact with the computer, like clicking 'X' to exit a window. Being text based, the command line executes tasks given by the user through commands in the terminal. It is the "old-school" method of interacting with the computer. For some, the command line is faster than the GUI, and theoretically one can control the entire computer with just this application. Though realistically, it's best to use a combination of the two methods.

## Basic Navigation

As stated before, navigating the computer through the terminal occurs by text commands issued by the user. There is a command for every action one may associate with a GUI. For instance, with the GUI, to create a new file, one could right-click > create new, or file > create new. But in the terminal the user would simply type one would type `touch some-file-name`. Of course there are many other commands that will become second nature with time, like change director `cd` or list `ls`, and it's useful to have a reliable resource to reference at any time.

## More About Files

The user can create a variety of files, namely .txt (or similar) and IDE file name (.js, .html, .css, etc...). It is important to know that the Linux terminal is case sensitive, so holiday.txt is not the same as Holiday.txt. Also note that the terminal has difficulties with multiple word file names and will need to be called with single quotes `''`, an escape `\` or, more commonly, write the file name with hyphens or camel-case. There are also hidden files can be created with a full stop `.` and accessed with `-a`, i.e. `.secret-file` or `ls -a`.

## Manual Pages

The manual pages are a useful reference feature built into linux based terminals an is accessed by command `man<something-to-lookup>`. For example, to learn more about the list option and its varieties, type `man ls` and discover that ls is short for list and be modifies with -a (all, even hidden). Key terms can be searched for with the -k modifier, as in `man -k <search-for-this>`.

## File Manipulation

File manipulation was touched on briefly before, but of course there are more commands than `touch`. Other must-knows are `mkdir` (make directory) which creates a new folder rather than a file, `cp` for copy, and `mv` for move (or rename). Sometimes the user needs to remove files or folders, in which case they would use the `rm` remove command either as `mkrm [your-dir-here]` or `rm -rf [your-object-name]` to wipe all related data.

## Cheat Sheet

It's always wise to have a reference handy. Here is a link to a comprehensive cheat sheet.

 -[Ryan's Tutorials](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)
