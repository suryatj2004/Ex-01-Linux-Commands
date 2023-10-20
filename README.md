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
 ![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/9f2f13c4-2223-432c-ae0a-0dac3b497700)



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/773db03a-549e-4e93-81a9-2cdf277b5466)


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/6e16abff-c735-40d1-9ff1-6827d325ec55)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/7653c1b0-f86e-4f3b-b818-4606670081f4)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/09bdcc89-6025-4435-9a37-37c2d7a6ba23)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/4c303edd-1882-4bf0-b0d2-c63ff201b47d)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/debbe35a-a664-47d6-915d-b127d419fd68)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/08ffd4de-f3cb-4f3b-baaa-40ee6639cb65)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/d5926cdf-94cc-45c4-a87b-e87b37d1404b)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/ed3e7402-d9a0-4bbe-909b-5cf3d2b25e92)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/5abb48df-f982-4787-80ed-a8c373782e7e)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/a5b59ff8-41f7-4e51-b2c4-a44bd0a5627d)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/d3edb1a3-3d3b-4ffa-a7a0-7b91924938a6)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/41fbcf79-9981-49e3-a086-bd81b6ff8c00)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/bd829aa4-224a-4519-b07c-724b5fd7ca44)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/c37324e7-bb5b-417a-a1b8-d56778c1419b)

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

![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/8b57ed28-985b-4645-8f67-0b2a97ee4a8b)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/a0929ac4-ec19-4f9a-8cf2-f0addae91592)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/ef47f927-ceaa-463a-97ce-fc18b607087b)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/0c1cc7ed-8286-4259-9ef3-28202d11bd4d)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/ee5872bb-bc18-46cb-918c-323eee469fd7)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/364faf2b-dcf0-410d-93c7-7bcb4d9a6ecb)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/661b7a21-68df-4689-9ddd-030888639128)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/86fceb10-5b78-4bd2-b19a-d6196245b841)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/c32be235-3a34-4ac3-a5a3-120da67c3354)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/Krishnakumar05/Ex-01-Linux-Commands/assets/119393130/d927b8af-d799-49c3-8649-16abecd291d5)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
