### Gives version
```
git --version
```
### font size
ctrl + scroll up-down
### Create File in working directory
```
touch file_name.txt
```
I type in bunch of stuff in that file seperately using any software
### initialize repository
```
git init
```
Initializes current working directory as repository. It ceates a hidden ,git folder inside that directory
### add name and email address to git
to do that use this command:
```
git config --global user.name 'Habib ur rehman'
git config --global user.email 'mrhabib214@gmail.com'
```
### add files to our repository
```
git add file_name.txt
```
Adds a specific file
```
git add .
```
It adds all files
### show status of git
```
git status
```
It also shows us which file are not added yet to repository
### remove file
```
git rm --cached file_name.png
```
### commit changes of a file
to commit first change something in file.
check status and you'll see that it shows that file has been channged
```
git commit -m 'Comment whatever you want over here'
```


