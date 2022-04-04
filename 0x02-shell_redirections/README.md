
# Shell permissions
DevOps shell permissions workspace

### About Bash permissions commands
### 

### 
#### Script that prints “Hello, World”, followed by a new line to the standard output.
> echo 'Hello World'

###
![Hello World](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/0-hello_world.png)

### 
#### Script that displays a confused smiley "(Ôo)'.
> echo "\"(Ôo)'"
###
![Confused smiley](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/1-confused_smiley.png)

### 
#### Display the content of the /etc/passwd file.
> cat /etc/passwd
###
![Let's display a file](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/2-hellofile.png)

### 
#### Display the content of /etc/passwd and /etc/hosts
> cat /etc/passwd /etc/hosts
###
![What about 2?](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/3-twofiles1.png)
![What about 2?](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/3-twofiles.png)

### 
#### Display the last 10 lines of /etc/passwd
> tail -n 10 /etc/passwd
###
![Last lines of a file](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/4-lastlines.png)

### 
#### Display the first 10 lines of /etc/passwd
> head -n 10 /etc/passwd
###
![I'd prefer the first ones actually](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/5-firstlines.png)

###
#### Script that displays the third line of the file iacta.
> head -n 3 iacta | tail -n 1
###
![Line #2](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/6-third_line.png)

###
#### Shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
> echo "Best School" > '\*\\'\''"Holberton School"\'\''\\*$\?\*\*\*\*\*:)'
###
![It is a good file that cuts iron without making a noise](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/7-file.png)

###
#### Script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
> ls -la > ls_cwd_content
###
![Save current state of directory](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/8-cwd_state.png)

###
#### Script that duplicates the last line of the file iacta
> tail -1 iacta >> iacta
###
![Duplicate last line](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/9-duplicate_last_line.png)

###
#### Script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
> find -name "*.js" -type f -delete
###
![No more javascript](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/10-no_more_js1.png)
![No more javascript](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/10-no_more_js2.png)

###
#### Script that counts the number of directories and sub-directories in the current directory.
> find -mindepth 1 -type d | wc -l
###
![Don't just count your directories, make your directories count](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/11-directories.png)

###
#### Script that displays the 10 newest files in the current directory.
> ls -t | head -10
###
![What’s new](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/12-newest_files.png)

###
#### Script that takes a list of words as input and prints only words that appear exactly once.
> sort | uniq -u
###
![Being unique is better than being perfect](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/13-unique.png)

###
#### Display lines containing the pattern “root” from the file /etc/passwd
> grep root /etc/passwd
###
![It must be in that file](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/14-findthatword.png)

### 
#### Display the number of lines that contain the pattern “bin” in the file /etc/passwd
> grep bin /etc/passwd | wc -l
### Or
> grep -c bin /etc/passwd
###
![Count that word](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/15-countthatword.png)

### 
#### Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
> grep root /etc/passwd --after-context=3
###
![What's next?](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/16-whatsnext.png)

### 
#### Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
> grep -v bin /etc/passwd
###
![I hate bins](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/17-hidethisword.png)

### 
#### Display all lines of the file /etc/ssh/sshd_config starting with a letter.
> grep '^[[:alpha:]]' /etc/ssh/sshd_config
###
![Letters only please](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/18-letteronly.png)

### 
#### Replace all characters A and c from input to Z and e respectively.
> tr A Z | tr c e
###
![A to Z](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/19-AZ.png)

### 
#### Script that removes all letters c and C from input.
> tr -d C | tr -d c
###
![LWithout C, you would live in hiago](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/20-hiago.png)

### 
#### Script that reverse its input.
> rev
###
![esreveR](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/21-reverse.png)

### 
#### Script that displays all users and their home directories, sorted by users.
> cut -d : -f 1,6 /etc/passwd | sort
###
![DJ Cut Killer](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/22-users_and_homes.png)

##Advanced tasks

### 
#### Command that finds all empty files and directories in the current directory and all sub-directories.
> find . -empty -printf "%f\n"
###
![Empty casks make the most noise](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/100-empty_casks.png)

### 
#### Script that displays all users and their home directories, sorted by users.
> find . -name "*.gif" -type f -printf "%f\n" | rev | cut -d. -f2- | rev | LC_ALL=C sort -f
###
![A gif is worth ten thousand words](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/101-gifs.png)

### 
#### Script that decodes acrostics that use the first letter of each line.
> telnet towel.blinkenlights.nl
###
![Acrostic](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/102-acrostic.png)

### 
#### Script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
> telnet towel.blinkenlights.nl
###
![The biggest fan](https://github.com/Cocorine/alx-system_engineering-devops/blob/main/resources/redirections/103-the_biggest_fan.png)
