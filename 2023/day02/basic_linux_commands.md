## Basic linux commands

Day 2 Task: Basics linux command

Task: What is the linux command to

Check your present working directory.
List all the files or directories including hidden files.
Create a nested directory A/B/C/D/E
Note: Check this file for reference



A Linux command is like a magic word you tell your computer to make it do something. It's a way for you to give instructions to your computer's operating system (in this case, Linux) by typing specific words or phrases. These instructions can be as simple as asking the computer what time it is or as complex as telling it to copy, move, or delete files, install software, or even start and stop programs

Check Your Present Working Directory (PWD):

Command: pwd
Description: The "pwd" command stands for "Print Working Directory." It displays the absolute path of the current directory you are in. This is a fundamental command for knowing where you are within the file system.
List All Files or Directories, Including Hidden Files (LS):

Command: ls -a
Description: The "ls" command is used to list the contents of a directory. Adding the "-a" option shows not only the visible files and directories but also hidden ones, which are typically denoted by a leading dot (e.g., .hiddenfile).
Create a Nested Directory (MKDIR):

Command: mkdir -p A/B/C/D/E
Description: The "mkdir" command is used to create directories. In this case, the "-p" option tells it to create the entire directory tree, even if intermediate directories (A, B, C, D) don't exist. This way, you'll end up with a nested directory structure A/B/C/D/E


<img width="919" alt="image" src="https://github.com/birvagangurde/90DaysOfDevOps/assets/98297625/a39af9fc-33b4-498d-8ab4-a22d9dbf78a9">

<img width="745" alt="image" src="https://github.com/birvagangurde/90DaysOfDevOps/assets/98297625/7fce7da5-55d7-4e25-8a98-e51e9bf1abe6">

The following are Beginners Linux commands :- 
ls — Use the "ls" command to know what files are in the directory you are in. You can see all the hidden files by using the command “ls -a”.

cd — Use the "cd" command to go to a directory. For example, if you are in the home folder, and you want to go to the downloads folder, then you can type in “cd Downloads”. Remember, this command is case sensitive, and you have to type in the name of the folder exactly as it is. But there is a problem with these commands. Imagine you have a folder named “Raspberry Pi”. In this case, when you type in “cd Raspberry Pi”, the shell will take the second argument of the command as a different one, so you will get an error saying that the directory does not exist. Here, you can use a backward slash. That is, you can use “cd Raspberry\ Pi” in this case. Spaces are denoted like this: If you just type “cd” and press enter, it takes you to the home directory. To go back from a folder to the folder before that, you can type “cd ..” . The two dots represent back.

mkdir & rmdir — Use the mkdir command when you need to create a folder or a directory. For example, if you want to make a directory called “DIY”, then you can type “mkdir DIY”. Remember, as told before, if you want to create a directory named “DIY Hacking”, then you can type “mkdir DIY\ Hacking”. Use rmdir to delete a directory. But rmdir can only be used to delete an empty directory. To delete a directory containing files, use rm.

rm - Use the rm command to delete files and directories.  Use "rm -r" to delete just the directory. It deletes both the folder and the files it contains when using only the rm command.

touch — The touch command is used to create a file. It can be anything, from an empty txt file to an empty zip file. For example, “touch new.txt”.

man & --help — To know more about a command and how to use it, use the man command. It shows the manual pages of the command. For example, “man cd” shows the manual pages of the cd command. Typing in the command name and the argument helps it show which ways the command can be used (e.g., cd –help).

cp — Use the cp command to copy files through the command line. It takes two arguments: The first is the location of the file to be copied, the second is where to copy.

mv — Use the mv command to move files through the command line. We can also use the mv command to rename a file. For example, if we want to rename the file “text” to “new”, we can use “mv text new”. It takes the two arguments, just like the cp command.

locate — The locate command is used to locate a file in a Linux system, just like the search command in Windows. This command is useful when you don't know where a file is saved or the actual name of the file. Using the -i argument with the command helps to ignore the case (it doesn't matter if it is uppercase or lowercase). So, if you want a file that has the word “hello”, it gives the list of all the files in your Linux system containing the word "hello" when you type in “locate -i hello”. If you remember two words, you can separate them using an asterisk (*). For example, to locate a file containing the words "hello" and "this", you can use the command “locate -i *hello*this”.

Thank you!



