# Git-Linux-Commands
Here have mentioned some useful and important commands for Git and linux

## Git commands

### 1)git init

Initializes a new Git repository in the current directory.

### 2)git clone

 Clones an existing Git repository from a remote source to your local machine. 
 Can also be helpful in regards of Docker when you want to retrieve source code from a remote repository to build your Docker image
 
 ### 3)git tag
 
 Creates new tags, lists existing tags, and manages tags in a Git repository. Can also be used when want to mark a specific version of your code for release.
 
 ### 4)git status
 
  Displays the current state of the repository, including changes that have not been staged or committed.
  
 ### 5)git branch
  
 Manages branches in a Git repository, including creating new branches and switching between branches.
 This command can be used in sense Docker as well specially when you want to test different features or bug fixes in a separate branch before merging them into the main branch.

### 6)git stash 

Temporarily saves changes that have not been committed, allowing you to switch to another branch.

### 7)git pull

loads changes from a remote repository and merges them into the local branch

### 8)git diff

Shows differences between commits, branches, and more.
This is useful in Docker when you want to see the changes in your source code and how it affects your Docker image.

### 9)git merge

merges the histories of the branches and changes from one branch into another. When merging several branches into a single branch for deployment in Docker, this is helpful.

### 10)git revert 

Git command that allows you to undo changes to the repository by creating a new commit that reverses the changes introduced in one or more previous commits.
You would specify the commit hash or a reference to the commit that you want to undo.

## Linux Commands 

Below are mentioned some commands of linux that are useful in many aspects

### 1)grep 

Searches files for lines that match a given pattern.

### 2)sed 

Cmmand modifies lines from the specified File parameter according to an edit script and writes them to standard output.

### 3)awk 

select data – one or more pieces of individual text – based on a pattern you provide.

### 4)find 

Searches for files and directories based on various criteria.

### 5)top 

Displays real-time information about system processes and resource usage.

### 6)ps 

Displays information about the running processes on the system.

### 7)kill 

The kill is a very useful command in Linux that is used to terminate the process manually. It sends a signal which ultimately terminates or kills a particular process or group of processes.

### 8)man

The man command provides reference information on topics, such as commands, subroutines, and files. The man command provides one-line descriptions of commands specified by name

### 9)chmod

Changes the permissions of files and directories.

### 10)rsync 

Synchronizes files and directories between local and remote systems.


