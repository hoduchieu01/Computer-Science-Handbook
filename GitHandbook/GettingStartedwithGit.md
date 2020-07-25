# Git Handbook - Getting Started with Git

## What is a version control system ?

A version control system tracks the history of changes as people and teams collaborate on projects together. It keeps track all the modifications of source code in a database and help any software developer to manage changes
to source code of a product.

## Why is Git ?

Git is an <b>open-source distributed version control system</b>. According to the [Stack Overflow developer survey 2017](https://insights.stackoverflow.com/survey/2017#technology), more than 70 percent of developers use Git, making it the most-used VCS in the world. Git is commonly used for both open source and commercial software development, <b> with significant benefits </b> for individuals, teams and businesses. [1]

According to the [Stack Overflow developer survey 2020](https://insights.stackoverflow.com/survey/2020), more than 82% of the professional developers who responded to the survey use Github as a collaborative tool. Github is now owned by Microsoft.

## What is a repository ?

A repository, or Git project, encompasses the entire collection of files and folders associated with a project, along with each file’s revision history. The file history appears as snapshots in time called commits, and the commits exist as a linked-list relationship, and can be organized into multiple lines of development called branches. Because Git is a distributed version control system, repositories are self-contained units and anyone who owns a copy of the repository can access the entire codebase and its history. Using the command line or other ease-of-use interfaces, a git repository also allows for: interaction with the history, cloning, creating branches, committing, merging, comparing changes across versions of code, and more. [1]

## Get started on using Git

### Getting Started - Installing Git
  
Before you start using Git, you have to make it available on your computer.

[Download Git](https://git-scm.com/downloads)

After installing, you can verify if Git is installed in your computer by using this command.

```git --version```

### Basic Git Commands

To use Git, developers should know how to use specific commands to create, change, copy and combine code. There commands can be used directly through command line or using an application such as GitHub Desktop (computer), GitKraken (computer) or Working Copy (mobile phone or tablet). 

If you are a student, you can apply [GitHub Student Developer Pack](https://education.github.com/pack/) to have a free access to these tools.

Here are some common commands for getting started with Git:

```git init```: initializes a brand new Git repository and begins tracking an existing directory

```git clone```: creates a local copy of a project that already exists remotely 

Clone this project: ```git clone https://github.com/hoduchieu01/Computer-Science-Handbook.git ```
```git add .```: stages a change and tracks changes to a developer's codebase

```git commit -m "message"```: saves the snapshot to the project history and completes the change-tracking process

```git status```: shows the status of changes

```git branch```: shows the branches being worked on locally

```git merge```: merges lines of development together, typically used to combine changes made on two distinct 
branches

```git pull```: updates the local line of development with updates from its remote counterpart

```git push```: updates the remote repository with any commits made locally to a branch.
  
## REFERENCES
[Git Handbook](https://guides.github.com/introduction/git-handbook/)
