# Basic_Linux_Commands
Brush Up your linux skills here with most of the basic commands that all you will need.


### 1. To	find out the username/userid on your machine.
**echo $UID**

![image](https://user-images.githubusercontent.com/75159672/114263010-a5f66d00-9a00-11eb-97d8-ae63a026dd1d.png)


### 2.	To print the present working directory path.
**pwd**

![image](https://user-images.githubusercontent.com/75159672/114263211-dc80b780-9a01-11eb-964c-202315b9209b.png)


### 3.	To go to a given directory (change the directory).
**cd dirname**
  
![image](https://user-images.githubusercontent.com/75159672/114263235-ffab6700-9a01-11eb-9fa1-f70303cb07f5.png)


### 4.	Command to view the information about a Linux/Unix command? Try to know about the commands “ls”.
**man ls**

![image](https://user-images.githubusercontent.com/75159672/114263286-38e3d700-9a02-11eb-8a9e-f1ce68b88429.png)


### 5.	The options for printing all the groups associated to a user with name.
**id -G**

![image](https://user-images.githubusercontent.com/75159672/114263330-7183b080-9a02-11eb-90c0-3e808bab4739.png)


### 6.	Create a file called “ctest”. Modify the access permissions as: “user - rwx”, “group - rx”, and “others - nothing”.
**touch ctest  to create a file**
**chmode -rwx-r-x-- ctest .. to provide permission as: “user - rwx”, “group - rx”, and “others - nothing”.**

![image](https://user-images.githubusercontent.com/75159672/114263355-9a0baa80-9a02-11eb-9fe5-5a371f7f9346.png)


### 7.	Create a 3 level directory in your home directory as shown in the structure below with single command.
### mydir
### |
### Sudhir1
### |
### Sudhir
**mkdir -p /home/subdir1/subdir**


### 8. Now move the whole directory i.e. mydir to mydir1 and change the permissions as owner-rwx, group-rx, others-x.
**mv home home1**
**chmod  home1**

![image](https://user-images.githubusercontent.com/75159672/114263410-e7881780-9a02-11eb-9fe3-084788c732c8.png)


### 9. Create a text file using an editor with content as: Welcome to ACTS courses.
### First day is about Linux.
### It’s a very commonly used OS.
### Simple to understand and work. Many os are based on LINUX.
### All linux OS are open source and freely available
**touch filename**

**vi filename**

**insert text into it using**

![image](https://user-images.githubusercontent.com/75159672/114270049-d3a2dc80-9a27-11eb-8a5c-8a0e74b1d218.png)


### a)	From the file get the count of word “Linux” it must also include LINUX while counting
**grep -ci linux filename**

### b)	Display lines that exactly have the word ‘OS’
**grep -c OS filename**

### c)	Display the line number where appears word ‘Linux’ irrespective of case
**grep -ni linux filename**


### 10.	Create a file “test” in the directory /home/cdac/mydir1/subdir1/test. Go to the home directory and now find the file “test” executing the appropriate command
**find -name test**

![image](https://user-images.githubusercontent.com/75159672/114270159-7bb8a580-9a28-11eb-9f3d-303155e6d34d.png)


### 11.	From home directory list all the files including the hidden files.
**ls -al**

### 12. display text from txt file without opening it.
**head -n2 filename.txt**

### b) display last 2 lines from it.
**tail -n2 filename.txt**

### c) display exactly 10th line from it.
**cat filename.txt |head -10|tail -1**

### 13. zinpping and unzipping
### a) to zip files into a zip
**tar cvf file.tar file1-file2-file3**

### b) unziping it
**tar xvf file.tar**

















