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

# Change group ownership

```

=> using chgrp command we can change the group ownership.
=> using this command we can check the file ownership & group ownership like this
 Ls –l <file name>
=> here we can the group ownership is installation.
=> now we will change the group ownership from installation to root using this command.

sudo chgrp root first.txt
```

<img src="images/21.png">

========================================================================================================

# Vi or Vim for file editing

=> we can easily edit the file using vi editor.

```
1) vi <file name>
```
<img src="images/22.png">

```

2) vi editor will open
```
<img src="images/23.png">

```

3) now if we want to insert then press I so it will convert into insert mode so
we can insert content.
```

<img src="images/24.png">

```
4) now after inserting press ESC.
```

```
5) then press : and write wq like this :wq it will save the file and exit from the vi
editor and go back to the terminal like this.
```

<img src="images/25.png">

```
6) it will back to the terminal
```
<img src="images/26.png">

========================================================================================================

# How to Search in Vim/Vi

```
1) first of all we have to open the any file in vi editor.
2) press ESC
3) then we have to write like this :
%s/(searching element)
Let's take an example.
```

<img src="images/27.png">

========================================================================================================

# How Do You Do A Search And Replace in Vim/Vi

```
1) first of all we have to open the any file in vi editor.
2) press ESC
3) then we have to write like this :
%s/(searching element)/(enter text you want tor replace)
* Here we search the language and then replace it with lan.
```
<img src="images/28.png">

<img src="images/29.png">
