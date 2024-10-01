
[1. What is Unix?](#1.-What-is-Unix?)
[2. List the distributions of UNIX.](#2.-List-the-distributions-of-UNIX.)
[3. List some features of UNIX.](#3.-List-some-features-of-UNIX.)
[4. What are the core concepts of UNIX](#4.-What-are-the-core-concepts-of-UNIX)
[5. What is a UNIX shell?](#5.-What-is-a-UNIX-shell?)
[6. What is filter?](#6.-What-is-filter?)
[7. What are the devices represented in UNIX?](#7.-What-are-the-devices-represented-in-UNIX?)
[8. Is there any method to erase all files in the current directory, along with its all sub-directories, by using only one command?](#8.-Is-there-any-method-to-erase-all-files-in-the-current-directory,-along-with-its-all-sub-directories,-by-using-only-one-command?)
[9. What is necessary before running a shell script from the terminal?](#9.-What-is-necessary-before-running-a-shell-script-from-the-terminal?)
[10. How to terminate a shell script if statement?](#10.-How-to-terminate-a-shell-script-if-statement?)
[11. Write down some common shells with their indicators?](#11.-Write-down-some-common-shells-with-their-indicators?)
[12. What are the main features of Korn Shell?](#12.-What-are-the-main-features-of-Korn-Shell?)
[13. What is the difference between cat command and more command?](#13.-What-is-the-difference-between-cat-command-and-more-command?)
[14. Which command is used to restrict incoming messages?](#14.-Which-command-is-used-to-restrict-incoming-messages?)
[15. Which command is used to kill the last background job?](#15.-Which-command-is-used-to-kill-the-last-background-job?)
[16. Which data structure is used to maintain the file identification?](#16.-Which-data-structure-is-used-to-maintain-the-file-identification?)
[17. What a pipe?](#17.-What-a-pipe?)
[18. What are the links and symbolic links in a UNIX file system?](#18.-What-are-the-links-and-symbolic-links-in-a-UNIX-file-system?)
[19. Explain system bootup in UNIX.](#19.-Explain-system-bootup-in-UNIX.)
[20. How to change the password in UNIX operating system?](#20.-How-to-change-the-password-in-UNIX-operating-system?)
[21. How to list directories in UNIX?](#21.-How-to-list-directories-in-UNIX?)
[22. How to check the date in UNIX?](#22.-How-to-check-the-date-in-UNIX?)
[23. How to log out in UNIX?](#23.-How-to-log-out-in-UNIX?)
[24. How to perform a system shutdown in UNIX?](#24.-How-to-perform-a-system-shutdown-in-UNIX?)
[25. How many types of files are there in UNIX?](#25.-How-many-types-of-files-are-there-in-UNIX?)
[26. What are hidden files in UNIX?](#26.-What-are-hidden-files-in-UNIX?)
[27. What is the difference between a single dot and double dot in UNIX?](#27.-What-is-the-difference-between-a-single-dot-and-double-dot-in-UNIX?)
[28. How to create files in UNIX?](#28.-How-to-create-files-in-UNIX?)
[29. How to display the contents of a file?](#29.-How-to-display-the-contents-of-a-file?)
[30. How to calculate the number of words in a file?](#30.-How-to-calculate-the-number-of-words-in-a-file?)
[31. How to create a blank file in UNIX?](#31.-How-to-create-a-blank-file-in-UNIX?)
[32. How to know the present working directory in UNIX?](#32.-How-to-know-the-present-working-directory-in-UNIX?)
[33. How to know the information about a file?](#33.-How-to-know-the-information-about-a-file?)
[34. How to change the directory in UNIX?](#34.-How-to-change-the-directory-in-UNIX?)
[35. How to move files from one directory to other in UNIX?](#35.-How-to-move-files-from-one-directory-to-other-in-UNIX?)
[36. How to copy files from one directory to other in UNIX?](#36.-How-to-copy-files-from-one-directory-to-other-in-UNIX?)
[37. How to remove files in UNIX?](#37.-How-to-remove-files-in-UNIX?)
[38. How to make a new directory in UNIX?](#38.-How-to-make-a-new-directory-in-UNIX?)
[39. How to remove the directory in UNIX?](#39.-How-to-remove-the-directory-in-UNIX?)




# back-to-top









# 1.-What-is-Unix?


UNIX is a portable operating system that is designed for efficient multitasking and multi-user functions. Since it is a portable operating system, it can run on different hardware platforms. It is written in C language. It was developed by Ken Thompson, Dennis Ritchie, Douglas McIlroy, and Joe Ossanna.

[back to top](#back-to-top)

# 2.-List-the-distributions-of-UNIX.


UNIX has many distributions including Solaris UNIX, AIX, HP UNIX and BSD and many more.

[back to top](#back-to-top)

# 3.-List-some-features-of-UNIX.

UNIX includes the following features:

<span style="background:#ff4d4f">**UNIX supports the multiuser system-:**</span> 
In UNIX it is possible that many users can use the system with their separate workspace and logins i.e.it has full support for the multiuser environment.

<span style="background:#ff4d4f">**UNIX supports the multitasking environment:-**</span> 
In UNIX many apps can run at a single instance of time this is also known as a multitasking environment.

[back to top](#back-to-top)

# 4.-What-are-the-core-concepts-of-UNIX

<span style="background:#ff4d4f">The core concepts of UNIX are given below.</span>

<span style="background:#d4b106">Kernel-</span>
The kernel is also known as the heart of the operating system. Its fundamental role is to interact with the hardware and also monitor major processes like memory management, file management, and task scheduling.

<span style="background:#d4b106">Shell-</span> It is also called command prompt, it connects the user to the operating system, whatever is typed by the user is translated into the language understood by the command prompt, and then the corresponding actions are performed.

<span style="background:#d4b106">Commands and Utilities-</span> Many built-in commands help the user perform day to day activities.mv,cat,cp,and grep etc. Some of the examples

<span style="background:#d4b106">Directories-</span> Every bit of data is stored in files, and these files are stored in directories, these directories combine to form a tree-like structure.

[back to top](#back-to-top)

# 5.-What-is-a-UNIX-shell?

The UNIX shell is a program which is used as an interface between the user and the UNIX operating system. It is not a part of the kernel, but it can communicate directly with the server.

[back to top](#back-to-top)

# 6.-What-is-filter?

A filter is a program that takes input from standard inputs and performs some operation on that input to produce a result as standard output.
[back to top](#back-to-top)

# 7.-What-are-the-devices-represented-in-UNIX?

All devices in UNIX are represented by particular files that are located in /dev directory.

[back to top](#back-to-top)

# 8.-Is-there-any-method-to-erase-all-files-in-the-current-directory,-along-with-its-all-sub-directories,-by-using-only-one-command?

Yes, you should use "rm-r*" command for this purpose.

Here, the "rm" command is used for deleting files, the -r option will erase directories and subdirectories with their internal data and * is used for selecting all entries.

---

[back to top](#back-to-top)

# 9.-What-is-necessary-before-running-a-shell-script-from-the-terminal?

You must make the shell script executable by using the UNIX "chmod" command.

---

# 10.-How-to-terminate-a-shell-script-if-statement?

A shell script if statement can be terminated by using "fi."

---

[back to top](#back-to-top)

# 11.-Write-down-some-common-shells-with-their-indicators?

- sh - Bourne shell

- csh - C Shell

- bash - Bourne Again Shell

- tcsh - enhanced C Shell

- zsh - Z Shell

- ksh - Korn Shell

---

[back to top](#back-to-top)

# 12.-What-are-the-main-features-of-Korn-Shell?

- Arrays

- Job control

- Command Aliasing

- String manipulation ability

- Built-in integer arithmetic

---

[back to top](#back-to-top)

# 13.-What-is-the-difference-between-cat-command-and-more-command?

The cat command is used to display the file contents on the terminal, whereas more command is used like a pager which displays the screen page by page If the file is large and you have to scroll off the screen before you view it.

---

[back to top](#back-to-top)

# 14.-Which-command-is-used-to-restrict-incoming-messages?

The "mesg" command is used to restrict incoming messages.

---

[back to top](#back-to-top)

# 15.-Which-command-is-used-to-kill-the-last-background-job?

The "kill $!" Command is used to kill the last background job.

---

[back to top](#back-to-top)

# 16.-Which-data-structure-is-used-to-maintain-the-file-identification?

The "inode" data structure is used to maintain the file identification. Each file has a separate inode and a unique inode number.

---

[back to top](#back-to-top)

# 17.-What-a-pipe?

A pipe is used to join two or more commands by using a pipe "I" character. The output of the first command is propagated to the second command through the pipe.

---

[back to top](#back-to-top)

# 18.-What-are-the-links-and-symbolic-links-in-a-UNIX-file-system?

A link is a second name for a file. Links are used to assign more than one name to a file, but cannot be used to designate a directory more than one name or link filenames on different computers.

Symbolic links are the files that only contain the name of another file. The operations on the symbolic link are directed to the file pointed by it. Both the limitations of connections are eliminated in symbolic links.

---

[back to top](#back-to-top)

# 19.-Explain-system-bootup-in-UNIX.

System bootup is the first thing that takes place when the power button is pressed in UNIX. Whenever the power button is pressed, BIOS is fired up and checks if all the hardware connected to the system are working correctly, after being successful the system asks the user to provide authentication.

---

[back to top](#back-to-top)

# 20.-How-to-change-the-password-in-UNIX-operating-system?

To change the password in UNIX operating system :

1. Type in the command passwd.
2. You will get a screen which prompts to enter your default(current. password, type your current password.
3. if the current password is verified, then the terminal will prompt you to enter the new password.
4. Enter the new password twice, and your password will be updated.

---

[back to top](#back-to-top)

# 21.-How-to-list-directories-in-UNIX?

Command ls can be used to list directories in command prompt. Also, we can also use a variety of ls commands like:

|   |   |
|---|---|
|ls -a|In Linux, hidden files start with. (dot. Symbol and they are not visible in the regular directory. The (ls -a. command will enlist the whole list of the current directory including the hidden files.|
|ls -l|It will show the list in a long list format.|
|ls -lh|This command will show you the file sizes in human readable format. Size of the file is tough to read when displayed regarding a byte. The (ls -lh.command will give you the data regarding Mb, Gb, Tb, etc.|
|ls -lhS|If you want to display your files in descending order (highest at the top. according to their size, then you can use (ls -lhS. command.|
|ls -l - -block-size=[SIZE]|It is used to display the files in a specific size format. Here, in [SIZE] you can assign size according to your requirement.|
|ls -d */|It is used to display only sub directories.|
|ls -g or ls -lG|With this, you can exclude column of group information and owner.|
|ls -n|It is used to print group ID and owner ID instead of their names.|
|ls --color=[Value]|This command is used to print list as colored or discolored.|
|ls -li|This command prints the index number if the file in the first column.|
|ls -p|It is used to identify the directory easily by marking the directories with a slash (/. line sign.|
|ls -R|It will display the content of the sub-directories also.|
|ls -lX|It will group the files with the same extensions together in the list.|
|ls -lt|It will sort the list by displaying a recently modified file at the top.|
|ls ~|It gives the contents of the home directory.|
|ls ../|It gives the contents of the parent directory.|
|ls –version|It checks the version of ls command.|

---

[back to top](#back-to-top)

# 22.-How-to-check-the-date-in-UNIX?

To display the date in UNIX use the **date** command in command prompt.

![Unix Interview Questions](file:///C:/Users/Abhik/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

---

[back to top](#back-to-top)

# 23.-How-to-log-out-in-UNIX?

To log out of UNIX type the **logout** command in the command prompt.

---

[back to top](#back-to-top)

# 24.-How-to-perform-a-system-shutdown-in-UNIX?

To perform system shutdown in UNIX, you can use the following commands:

- halt

- init 0

- init 6

- power off

- reboot

- shutdown

---

[back to top](#back-to-top)

# 25.-How-many-types-of-files-are-there-in-UNIX?

There are three kinds of files in UNIX:

- Ordinary files: An ordinary file is the one which contains data, text or program instructions.

- Directories: These include both ordinary files and special files.

- Special Files: These are the files which provide unique access to hardware such as hard drives, CD-Rom Drives e.t.c.

---

[back to top](#back-to-top)

# 26.-What-are-hidden-files-in-UNIX?

Hidden files in UNIX are the files which have a .(dot. before the file name. These files do not show up in the traditional file manager.

Common examples of hidden files are:

- .profile

- .kshrc

- .rhosts

- .cshrc

---

[back to top](#back-to-top)

# 27.-What-is-the-difference-between-a-single-dot-and-double-dot-in-UNIX?

**.(Single dot.**-represents the current directory

**..(Double dot.**-represents the parent directory.

---

[back to top](#back-to-top)

# 28.-How-to-create-files-in-UNIX?

Creating files in UNIX is simple. The User needs to use the vi editor to create new files.

Type **vi filename** in command prompt to create new files. We can also use the **touch** command to create a zero byte file.

---

[back to top](#back-to-top)

# 29.-How-to-display-the-contents-of-a-file?

The user can use the cat command followed by the filename to display the command of a file. This command should be entered in the command prompt. The syntax of the command is shown below.

**$ cat filename**

Where the cat is the command to view contents of the file specified by the filename. Also if you want the line number to be displayed along with the content, you can use cat command with option -b.

---

[back to top](#back-to-top)

# 30.-How-to-calculate-the-number-of-words-in-a-file?

To count the number of words in a file, Use the following command.

**$ wc filename**

Where wc is the command to count the number of words in the file specified by **filename**.

---

[back to top](#back-to-top)

# 31.-How-to-create-a-blank-file-in-UNIX?

Blank files can be created by using the touch command, the syntax for the touch command is as follows:

**$ touch filename**

![Unix Interview Questions](file:///C:/Users/Abhik/AppData/Local/Temp/msohtmlclip1/01/clip_image004.jpg)

---

[back to top](#back-to-top)

# 32.-How-to-know-the-present-working-directory-in-UNIX?

To know the present working directory, Run the following command on the terminal.

**$ pwd**


---

[back to top](#back-to-top)

# 33.-How-to-know-the-information-about-a-file?

To fetch the information about a file, use the following command.

**$ file filename**


---

[back to top](#back-to-top)

# 34.-How-to-change-the-directory-in-UNIX?

To change the directory, you can use the cd command in the terminal window. It changes the current directory to the specified directory.

**$ cd directory-name**


---

[back to top](#back-to-top)

# 35.-How-to-move-files-from-one-directory-to-other-in-UNIX?

In UNIX, mv command is used to move the file from one directory to some other directory.


`$ mv <file-name> <destination path>`



![[35.png]]


[back to top](#back-to-top)

# 36.-How-to-copy-files-from-one-directory-to-other-in-UNIX?

In UNIX, cp command is used to copy a file from one directory to some other directory. The syntax of the cp command is given below.

`$ cp -r source filename destination file name.`

The -r is used to copy all the content of a directory including sub-directories recursively.

![[Pasted image 20240930030818.png]]

[back to top](#back-to-top)

# 37.-How-to-remove-files-in-UNIX?

To remove files, you can use the rm command. The syntax of the rm command is given below.



`$ rm <filename>`


**we can use -r with the rm command to delete all the sub-directories recursively.**

![[Pasted image 20240930030958.png]]


[back to top](#back-to-top)

# 38.-How-to-make-a-new-directory-in-UNIX?

To make a new directory, you can use the mkdir command.

[[**$ mkdir <directory-name>**]]

![[Pasted image 20240930031033.png]]

[back to top](#back-to-top)


# 39.-How-to-remove-the-directory-in-UNIX?

To remove the directory, you can use the rmdir command. To use this command, use the following syntax.

[[**$ rmdir filename.**]]

![[Pasted image 20240930031113.png]]


[back to top](#back-to-top)





