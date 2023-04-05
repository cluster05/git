### View status of files
```git status```

### Stages

##### Stage 1 
**Move file/s from Working Directory to Staging Area file**

Moved specific file

```git add <file-name>```

Move all files

```git add .```

**Move file/s from Staging Area to Working Directory file (Initial Stage) **

Moved specific file

```git rm --cached <file-name>```

Move all files

```git rm --cached .```

**Move file/s from Staging Area to Working Directory file**

Moved specific file

```git rm --staged <file-name>```

Move all files

```git rm --staged .```

##### Stage 2

**Move files from Staging Area to Local Repository**

Note : Description -m is optional

```git commit -m "message for commit" -m "description of commit"```

<hr/>

### View committed Data 

It will show all the data from git Local Repository

```git log```

<hr/>

### Git Differance

Check changes between Working Area and Staging Area

```git diff```

Check changes between Staging Area and Repository Area

```git diff --staged```

Check changes between Working Area and Repository Area

```git diff head```

<hr/>

### How to GIT store the Data

+ GIT store the data in form of key and values 
+ Values is nothing but content of file
+ You give the values and it will calculate a key from it, that is nothing but hash
+ GIT calculate the heshes with SHA1 algorithm

<hr/>




