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

=> Basically cat command has a multiple use.
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

===================================================

# List all running process

=> Basically using ps command we can list the all running process like this

<img src="images/17.png">

===================================================

# Find particular process by it's name

=> we can find the particular process by it’s name using pidof command like this

<img src="images/18.png">

===================================================

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

===================================================

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

===================================================

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

===================================================

# How to Search in Vim/Vi

```
1) first of all we have to open the any file in vi editor.
2) press ESC
3) then we have to write like this :
%s/(searching element)
Let's take an example.
```

<img src="images/27.png">

===================================================

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

===================================================
===================================================

# Linux Practical Exam

### 1) Write a command to create new folder.

```
=> mkdir <folder name >
=> Here we are creating test folder using mkdir command.
```

<img src="images/30.png">

### 2) Write a command to find the current path of the folder.

```
=> pwd
=> using pwd command we can find the current path of the folder.
```

<img src="images/31.png">

### 3) write a command to move into new created folder.

```
=> cd
=> using cd command we can change the directory.
```

<img src="images/32.png">

### 4) write a command to create new file.

```
=> we can create a new file using 2 command touch & cat
=> touch <filename>
=> cat > <filename>
```

<img src="images/33.png">

### 5) write a command to add some content in a file.

```
=> we can add the content in file using cat > filename like this
```

<img src="images/34.png">

```
=> if we want to add content below the existing content then we can write command like this cat >> second.txt
```

<img src="images/35.png">

### 6) write a command to find a specific word from a file..

```
=> for find specific word from file we can use the grep command
=> grep option “search word” <file name>
```

<img src="images/36.png">

### 7) write a command to find the size of a file.

```
=> we can find the size of the file and folder using du –h command like this
```

<img src="images/37.png">

<img src="images/38.jpeg">

### 8) write a command to rename that file.

```
=> for rename the file we can use the mv command
=> mv [old file name] [new file name]
```

<img src="images/39.jpeg">

### 9) write a command to make a copy of a file with another name.

```
=> for make a copy of one file to another name we can use the cp command like this.
=> cp [source filename] [copy filename]
```

<img src="images/40.jpeg">

### 10) write a command to show the list of files in folder.

```
=> for the list of file or folder we can use the ls command.
=> ls command will only show the all files. ls –l command will show all the file with it’s permission like this
```

<img src="images/41.jpeg">

### 11) write a command to move that file to desktop.

```
=> for move the file from one folder to desktop we can use the mv command like this.
=> mv [filename] [destination]
```

<img src="images/42.jpeg">


### 12) write a command to change permissions of the file.

```
=> for change the file permission we can use the chmod command.
```

<img src="images/43.jpeg">

```
=> here we can see the in third.txt file
 - user has read & write permission.
 - group has read & write permission.
 - other user has only read permission.
=> now let’s change the permission of user. We will remove the write permission from the user and add execute permission like this
```

<img src="images/44.jpeg">

### 13) write a command to delete file.

```
=> for delete the file we can use the rm command like this.
=> rm [file name]
=> here we will remove the text.txt file using rm command
```

<img src="images/45.png">

### 14) write a command to delete created folder.

```
=> for deleting the folder we can use the rmdir command.
=> using rmdir we can remove those folder which does not contain any files.
=> here we will remove the test folder.
```

<img src="images/46.png">

### 15) write a command to command to find a any file on local machine.

```
=> for finding any file on local machine we can use the find command.
```

<img src="images/47.png">

### 16) write a command to create a zip of files from specific path on local machine.

```
=> using zip command we can create a zip file of any folder or file.
=> zip [zip file name] [existing file name]
```

<img src="images/48.png">

### 17) write a command to unzip.

```
=> for unzip the file we can use the unzip command.
=> unzip [zip folder name]
```

<img src="images/49.png">

### 18) write a command to download file from specific location on the internet.

```
=> for download the file from the specific location we can use the wget command.
=> wget[url]
```

<img src="images/50.jpeg">

### 19) Write command to see last 10 lines of a file.

```
=> basically for that we can use the tail command it will bydefault show the last 10 line of the file.
```

<img src="images/51.jpeg">

### 20) Write command to see history of a file.

```
=> For getting the file history we can use the stat command.
```

<img src="images/52.jpeg">




