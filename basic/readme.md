### View status of files
```git status```

### Stages

##### Stage 1 
**Move file/s from Working Directory to Staging Area file**

Moved specific file

```git add <file-name>```

Move all files

```git add .```

**Move file/s from Staging Area to Working Directory file (Initial Stage)**

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

View All commit in one line format

```git log --oneline```

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

### GIT Branching 
In Git, branches are a part of your everyday development process. Git branches are effectively a pointer to a snapshot of your changes.

[Visualizing GIT](https://git-school.github.io/visualizing-git)

**Create New Branch**

```git branch <new-branch-name>```

**Change Branch**

```git checkout <branch-name>```

###### ```-b``` flag will create new branch and checkout to that branch

```git checkout -b <new-branch-name>```

**View All Branch**

```git branch```

**Rename the branch**

Checkout to that branch

```git branch -m <new-branch-name>```

**Delete the branch**

Checkout to other branch from the branch you want to delete

```git branch -d <branch-name>```

<hr/>