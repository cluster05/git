### GIT
###### Distributed Version Control System
Git is version control system also known as VCS
Developed By : Linus Torvalds

<hr/>

VSC is the software designed to record the changes made to the file over the time.

Git gives us ability to revert the files or the set of files you made changes.

Git not only records the source code it also track the images, research paper or any types files.

**We have three kinds of Version Control System**
1. Local Version Control System
2. Centralized Version Control System
3. Distributed Version Control System

<hr/>

**How Git Work**

Compared to other VCS like subversion. Most operation in GIT requires local resources to operate.
If you're used to a CVCS where most operation have that network latency

For Example :
To browse the history of the project, Git doesn't need to go out to server to get the history and display it for you.

It simply reads it directly from your local database

If you want to see the changes between the current working file and the file a month ago

Git can look up the file a month ago and do a local difference calculation

There is no need to ask a remote server to do it or pull an older version of the file from the remote server to do it locally.

<hr/>

**Git Stage**
1. **Modified**  : Means that you have changed the file but have not committed it to your database yet
2. **Staged**    : Means that you have marked as modified file in its current version to go into your next commit snapshot
3. **Committed** : Means that the data is safely stored in your local database
4. **Stashed**   : Means that  changes you've made to your working copy so you can work on something else, and then come back and re-apply them later on.

<hr/>

#### Git Workflow

![git stages](../images/git-stages)

**Working Directory :**

The working tree is a single checkout of one version of the project. These files are pulled out of the compressed database in the Git directory and placed on disk for you to use or modify.

**Staging Area:**

The stagging area is file, generally contained in your Git repository, that stores information about what will go into your next commit.

**Repository Area:**

The Git directory is where Git stores the metadata and object database for your project. This is the most important part of Git, and it is what is copied when you clone repository from another computer

<hr/>

#### Git Configuration

Used when we use git to change the files in the project. Git uses this information to identify who has made the changes to the file.

**Configuration File** ( Note: Hierarchy follow from top to bottom)
1. Repository/Project : 

    scope : Local Level

    location : repository/.git/config

2. User Account :

    scope : Global Level

    location: Users/<username>/.gitconfig

3. System Level :

    scope : Git (Git Installation)
    
    location: /usr/local/etc/gitconfig

<hr/>

**Cheeck complete Git config**

``` git config --list --show-origin ```

**Remove a specific setting for a specific level of config**

``` git config --global --unset <config-name> ```

**Remove the specific section**

``` git config --global --remove-section user ```

<hr/>

#### Git Project
    
Initialize Git

``` git init  ```

Setting up users details [ local level ] 

``` git config --local <key> <value> ```

Setting up users details [ global level ]

``` git config --global <key> <value> ```

View user details 

```git config --list```




