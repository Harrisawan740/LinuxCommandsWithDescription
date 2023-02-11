## **Some of the important commands of Linux**

## 1.**chown**

The chown command is used to change the owner and/or group of files or directories in a Linux system.
chown [options] OWNER[:GROUP] FILE...


## 2.**curl**

curl is a command-line tool to transfer data to or from a server, using any of the supported protocols (HTTP, FTP, IMAP, POP3, SCP, SFTP, SMTP, TFTP, TELNET, LDAP or FILE). This command is powered by Libcurl. This tool is preferred for automation since it is designed to work without user interaction. It can transfer multiple file at once.
Syntax:
curl [options] [URL...]

## 3.**chmod**

This command is used to change the access permissions of files and directories.
Syntax:
chmod <permissions of user,group,others> {filename}

## 4.**find**

Search for files in a directory hierarchy. Use find /path/to/search -name

## 5.**ssh**

The ssh command is used to securely log in to a remote server and execute commands on that server.
Syntax:
ssh [options] user@host

## 6.**top** 

The top command is a system monitoring utility in Linux that provides a real-time view of the processes running on a system.

## 7.**lsof**

While working in Linux/Unix system there might be several file and folder which are being used, some of them would be visible and some not. lsof command stands for List Of Open File. This command provides a list of files that are opened. Basically, it gives the information to find out the files which are opened by which process. With one go it lists out all open files in the output console.
Syntax:
$lsof [option][user name]

## 8.**find**

The find command is a powerful utility in Linux that allows you to search for files and directories based on various criteria such as name, size, modification time, and permissions. 
Syntax:
find [path] [expression]

## 9.**export**

The export command in Linux is used to set environment variables. Environment variables are values that can be used by multiple applications and scripts on a system to store and retrieve data.
Syntax:
export VAR_NAME=value

## 10.**stress**

The stress command in Linux is a tool used to stress-test a system. It is used to simulate high system load by running multiple processes that consume a specified amount of system resources, such as CPU, memory, and I/O.
Syntax:
stress -c 4 -t 60





