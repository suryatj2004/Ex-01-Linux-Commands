# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

 ![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/673c19b6-fc87-4418-8c3f-3b58c06afa59)



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/44d02da2-acac-46cc-9b6c-625ac44fcc7d)


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/51ebef05-8a08-4f1f-933f-5419a977d6d4)



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/c9188ce5-a003-428c-9020-248c14e74f94)



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/83fc4da7-68b2-4fb8-ae05-35f381998261)



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/19103c6e-e6d5-491c-9f16-51a261fac9c0)


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/eccda2a2-8fae-44c7-8c01-b31b3ebcd66d)




### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/3f912592-65d2-425a-ab97-cfd2d74246bf)



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/3449f079-0e0f-4b99-a9a7-2cfc88a92d39)



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/1a77e703-a9f5-413b-8ad0-ea9b36201bb0)


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/52af305e-6134-42dc-b986-4563c3ee1819)



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/5e57afcb-ba64-44b4-bda3-199eb142f374)



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/ce8fa37a-b574-4627-90f0-b447320adb5c)


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/8034a3a4-bf00-4c95-895c-d742d1946733)



### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/de9831d1-203b-4917-981d-4d687ebb836c)



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/7d08be6d-356b-4788-ae2f-ae18536d39e2)


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

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/f4161591-d4e6-4e87-865c-86eef0c6b4c4)


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/683221f3-95f0-4e72-9bed-8e67db78c753)



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/20c2ad5d-2694-443e-a901-b7690c6daa5d)


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/09e8344d-8966-4208-80e6-0bd37474c96f)



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/0774a42a-04e0-4ed1-8bea-cec1c1a58739)



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/b0b909da-1619-40b4-8dfb-34cec3ba2d2d)


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/74c9ede7-8d03-4bfb-811b-b28ad3d46fac)



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/ca024464-aae9-48b5-8e9e-1fa2ea7b1e5d)



### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/613d977e-7048-426b-b392-84fcd32fe89c)


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![image](https://github.com/Kaviarasu510/Linuxcommands/assets/119392695/9098147c-76d5-46b2-9c35-42c5a5e4c33d)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
