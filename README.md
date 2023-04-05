# Manipulating Files and Directories
### 1) pwd command
``` => pwd command is used to show the location of current working directory. ```

<img src="images/1.png">

### 2) mkdir command

``` 
=> basically mkdir command is used for creating directory or folder.
=> mkdir <directory/folder name> 
```

<img src="images/2.png">

### 3) rmdir command
```

=> rmdir command is used for remove directory. But there is one condition using rmdir command we can remove only empty folder.
=> rmdir <folder/directory name>
```

<img src="images/3.png">

### 4) ls command
```

=> ls command is used for listing the file and directories.
=> using ls –l we can check the permissions of files and directories.
```

<img src="images/4.png">


### 5) cd command   
```

=> Basically cd command is used for change the directory.
=> cd <directory name>
```

<img src="images/5.png">

### 6) touch command  
```

=> basically touch command is used to create empty file.
=> touch <file name>
```

<img src="images/6.png">

### 7) rm commad 
```

=> rm command is used to remove the files.
=> when we want to remove directory that contain the files using rm –r command we can remove that particular directory.
=> rm [file name] / rm –r [directory name]
```

<img src="images/7.png">

### 8) cp command
```

=> cp command is used to make the copy of the files or directory.
=> cp [source file name] [copied file name]
```

 1) copy file

<img src="images/8.png">

 2) copy directory

<img src="images/9.png">


### 9) mv command
```

=> basically mv command is used for move the file or folder form one directory to another directory.
=> using mv command we can also rename the file.
=>move file : mv [source filename] [destination]
=> Rename File : mv [old file name] [new file name]
```

1) move file from one directory to another.

<img src="images/10.png">

2) move directory from one directory to other.

<img src="images/11.png">

3) rename the file using mv command
<img src="images/12.png">


### 10) cat command
```

=> Basicallt cat command has a multiple use.
```

1) create file
```
=> cat <file name>
```

<img src="images/13.png">


2) display content of file

<img src="images/14.png">

3) insert data into new file or existing file
<img src="images/15.png">

========================================================================================================

# List all file permissions with example

=> Basically in linux there has 3 types of user and 3 types of permissions.
```
* Types of user *
1) user
=> user denoted by u
2) group
=> group denoted by g
3) other user
=> other user denoted by o
```

```
* Types of Permissions *
1) read
=> it’s denoted by r
2) write
=> it’s denoted by w
3) Exectute
=> it’s denoted by e
```

=> we can check the file or directory permission using ls –l command like this

<img src="images/16.png">

========================================================================================================

# List all running process

=> Basically using ps command we can list the all running process like this

<img src="images/17.png">

========================================================================================================

# Find particular process by it's name

=> we can find the particular process by it’s name using pidof command like this

<img src="images/18.png">

========================================================================================================

# Change file owner and group

```

=> for change the file ownership there us chown cmd used.
=> for change the group ownership there is chgrp cmd used.
=> using this command we can check the file ownership & group ownership like this
 Ls –l <file name>
=> Here file ownership is rutul & group ownership is installation.
```

<img src="images/19.png">

```
=> sudo chown root first.txt = using this command we have change
the file ownership from rutul to root like this
```
<img src="images/20.png">

========================================================================================================

