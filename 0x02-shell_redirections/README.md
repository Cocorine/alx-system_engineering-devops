
# Shell permissions
DevOps shell permissions workspace

### About Bash permissions commands
### 

### 
#### Script that prints “Hello, World”, followed by a new line to the standard output.
> adduser betty

###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/0-iam_betty.png)

### 
#### Script that displays a confused smiley "(Ôo)'.
> whoami
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/1-who_am_i.png)

### 
#### Display the content of the /etc/passwd file.
> groups
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/2-groups.png)

### 
#### Display the content of /etc/passwd and /etc/hosts
> chown betty hello
###### Or
> sudo chown betty hello
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/3-new_owner.png)

### 
#### Display the last 10 lines of /etc/passwd
> touch hello
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/4-empty.png)

### 
#### Display the first 10 lines of /etc/passwd
> chmod u+x hello
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/5-execute.png)

###
#### Script that displays the third line of the file iacta.
> chmod ug+x,o+r hello
###### Or
> chmod u+x,g+x,o+r hello
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/6-multiple_permissions.png)

###
#### Shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
> chmod +x hello
###### Or
> chmod a+x hello
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/7-everybody.png)

###
#### Script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
> chmod 007 hello
###### Or
> chmod -rwx,o+rwx hello
###### Or
> chmod a-rwx,o+rwx hello
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/8-James_Bond.png)

###
#### Script that duplicates the last line of the file iacta
> chmod chmod 753 hello
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/9-John_Doe.png)

###
#### Script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
> chmod --reference=olleh hello
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/10-mirror_permissions.png)

###
#### Script that counts the number of directories and sub-directories in the current directory.
> chmod -R ugo+x .
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/11-directories_permissions.png)

###
#### Script that displays the 10 newest files in the current directory.
> mkdir -m 751 my_dir
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/12-directory_permissions.png)

###
#### Script that changes the group owner to school for the file hello.
> chgrp school hello
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/13-change_group.png)

###
#### Script that takes a list of words as input and prints only words that appear exactly once.
> sudo chown -R vincent:staff .
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/100-change_owner_and_group.png)

###
#### Display lines containing the pattern “root” from the file /etc/passwd
> chown -h vincent:staff _hello
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/101-symbolic_link_permissions.png)

### 
#### Display the number of lines that contain the pattern “bin” in the file /etc/passwd
> sudo chown --from=guillaume betty hello
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/102-if_only.png)

### 
#### Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
> telnet towel.blinkenlights.nl
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/102-if_only.png)

### 
#### Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
> telnet towel.blinkenlights.nl
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/102-if_only.png)

### 
#### Replace all characters A and c from input to Z and e respectively.
> telnet towel.blinkenlights.nl
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/102-if_only.png)

### 
#### Script that removes all letters c and C from input.
> telnet towel.blinkenlights.nl
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/102-if_only.png)

### 
#### Script that reverse its input.
> telnet towel.blinkenlights.nl
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/102-if_only.png)

### 
#### Script that displays all users and their home directories, sorted by users.
> telnet towel.blinkenlights.nl
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/102-if_only.png)

##Advanced tasks

### 
#### Script that displays all users and their home directories, sorted by users.
> telnet towel.blinkenlights.nl
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/102-if_only.png)

### 
#### Script that displays all users and their home directories, sorted by users.
> telnet towel.blinkenlights.nl
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/102-if_only.png)

### 
#### Script that displays all users and their home directories, sorted by users.
> telnet towel.blinkenlights.nl
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/102-if_only.png)

### 
#### Script that displays all users and their home directories, sorted by users.
> telnet towel.blinkenlights.nl
###
![My name is Betty](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/permissions/102-if_only.png)
