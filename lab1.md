# Lab 1: Markdown, URLs and Paths
Caitlin McCallum
___
## cd command
**a. with no arguements:**

i. PHOTO

ii. *Working directory when command was run:*
> /home

iii. *Why I got this output:*
> I did not give the cd command a parameter, so cd did not change any directory.

iv. *Is this an error, if so then why?:*
> This is not an error, if it is it's a user error as this isn't the way cd is meant to be used.

**b. with a path to a directory as an argument:**

i. PHOTO

ii. *Working directory when command was run:*
> /home

iii. *Why I got this output:*
> the cd command with the lecture1/ arguement switches the current working directory to the given path.

iv. *Is this an error, if so then why?:*
> This is not an error.

**c. with a path to a file as an argument:**

i. PHOTO

ii. *Working directory when command was run:*
> /home/lecture1

iii. *Why I got this output:*
> cd is meant to navigate from path to path, not to a file. Hello.class is a file not a directory.

iv. *Is this an error, if so then why?:*
> This is an error, cd does not work with a file name as an arguement.
___
## ls command
**a. with no arguements:**

i. PHOTO

ii. *Working directory when command was run:*
> \home

iii. *Why I got this output:*
> ls listed the files at our given path, \home.

iv. *Is this an error, if so then why?:*
> no, not an error.

**b. with a path to a directory as an argument:**

i. PHOTO

ii. *Working directory when command was run:*
> \home

iii. *Why I got this output:*
> ls listed the files at the givien arguement, lecture1/.

iv. *Is this an error, if so then why?:*
> not an error.

**c. with a path to a file as an argument:**

i. PHOTO

ii. *Working directory when command was run:*
> /home/lecture1

iii. *Why I got this output:*
> ls lists the file name of the arguement given, Hello.java.

iv. *Is this an error, if so then why?:*
> not an error.
___
## cat command
**a. with no arguements:**

i. PHOTO

ii. *Working directory when command was run:*
> \home\lecture1

iii. *Why I got this output:*
> I got this output, an empty newline, because the cat command does not have a file path as input.

iv. *Is this an error, if so then why?:*
> This is an error because the cat command is meant to display the contents of a given file path to standard output. When the cat command is not given an input, it outputs a newline (and nothing else).

**b. with a path to a directory as an argument:**

i. PHOTO

ii. *Working directory when command was run:*
> /home

iii. *Why I got this output:*
> I got this output, "cat: lecture1/: Is a directory" because the cat command is meant to print the contents of a file, not a directory/folder.

iv. *Is this an error, if so then why?:*
> Yes, this is a user error. The cat command is not meant to be used for printing file contents, rather it's meant to print the contents of a file path given.

**c. with a path to a file as an argument:**

i. PHOTO

ii. *Working directory when command was run:*
> /home/lecture1/messages

iii. *Why I got this output:*
> I got this output because the parameter I used for the cat command was my french translation file. The cat command then printed the text contents of that file. 

iv. *Is this an error, if so then why?:*
> No, this is not an error.
___
