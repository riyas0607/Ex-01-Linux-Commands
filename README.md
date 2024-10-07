# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

## Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/0321ebed-f31a-4945-a8f5-3b13fea7be97)

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/9daa894c-8346-4d1f-881d-f14999c795c3)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/0518bbae-b72f-4c7d-b515-a00bb343669e)



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/4fe95406-b23d-4243-a3cd-3842e7104c9d)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/bc38b498-a150-45ef-a43d-89f724ab92cf)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

 ![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/0360e88f-16cf-415a-84db-00e46cb9752a)

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/a17128e9-dd5c-4e45-81a3-3ded27c3ca88)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/1c117574-db2f-4395-8031-e6f086c7999f)

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/2474b60e-124a-43f1-afa6-a0b7efa99020)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/5d7712cd-b7c4-4939-875d-89ec53177656)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/5f1dc87d-4833-4eb8-b056-e11e6614ac5e)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/d6734cb5-ae77-436f-b27c-14db4f05e519)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/7bcc5dc0-f53f-4bb8-95c6-56d10d386380)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/f1cfcf96-d5f8-4c30-82a1-447ade09396b)

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/51f039fd-dbea-461d-b641-0746a3feb280)

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/7d5b9fd7-adad-4a58-9e5e-ef9b39929ea6)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/7b7a456e-74e8-423b-a132-9d2109db09bb)


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/78eed5d3-6838-478f-b632-c46991d00a64)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/af42811e-990b-434d-b28f-4691d6ea4d16)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name

$chmod -R 777 /path/to/file/or/folder
 



### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/2d80e730-3ea1-4f00-8ec6-10c01afbdaec)

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/e06bb1ff-9509-48a1-b9af-1346e0bdc06d)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 ![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/7e4ac262-44e7-4637-9c4c-6bc5bad7ac08)

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/b32bf5f0-d866-4e3c-9566-b82720e09953)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/a227757a-9657-4c7d-99ee-0a78a8139823)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 ![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/b3f84e85-a1ef-4633-855a-afd0c819c693)

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![image](https://github.com/AfzaraThagsin/Ex-01-Linux-Commands/assets/127172501/470700d7-5d49-4891-8072-7107423b39da)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
