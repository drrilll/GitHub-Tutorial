# Git Tutorial 

This tutorial operates under the following assumptions

- OS: Ubuntu or some Linux Flavor 
- Git Version: 2.34.1 or later
- You have created a GitHub account at the following link <href>https://github.com/</href>


## Why Do We Use Git and Where?

Git is a *version control platform*, meaning that it is used to synchronize code changes in the cloud. This could be for multiple reasons, such as an emergency backup or for collaborating with others.

Git is used by 99% of the tech industry, as it is widely supported and allows for a secure way to store code in the cloud where it can be modified and re-uploaded by developers.

## Why Should You Use Git

Git is a clean way to backup code, and it also allows for you to write code from multiple devices. 

As previously mentioned, Git is a tool that will be around for a long time, and it is used by almost every tech company, so its a good skill to have! 


## Installing Git

Open a terminal and type the following commands individually:

The below commands are for updating your package manager, *apt* and for installing the Git-CLI (Command-Line Interface)

```
sudo apt-get update
```
``` 
sudo apt-get install git
```
----
The below commands are for configuring your global configuration file: ```~/.gitconfig```.  
Replace your_email with the email you used to create your git account.  
Replace your_name with your name. 
```
git --config user.email your_email
```
```
git --config user.name your name
```

Now you should all of your basic configuration setup, now we are going to work on initializing a repository and setting up your ssh key.

---

## Branches

Branches are one of the two main concepts of Git.

In every repository, there is a **primary branch**, sometimes called the **main** or **master** branch, varying from repository to repository. 

Picture a branch as a horizontal line, with a plethora of dots plotted on it. Each dot on the branch is called a **commit**. Commits are simply code changes that are added to the end of a given branch. All of the code changes ever made in a repository are reflected in branches.

**You can (and should) branch off of the primary branch.** Your branch originates from a given commit in a repository and runs **parallel to the primary branch.** Doing this allows you to make changes to the code base without them being made in the primary branch, while still keeping up with the changes made in the primary branch. **You can experiment with your changes and test them separately from the primary branch, on your own branch.**

You can create a new branch with the following command:

```
git branch <branchName>
```

You then need to "check out" the branch, switching your local file structure and files to match the branch, so your changes and future commits affect your new branch as opposed to the primary branch. You can do so with the following command.

```
git checkout <branchName>
```
Return to the primary branch at any time with the command:

```
git checkout <primaryBranchName>
```

Note that there are two types of branches, **local branches** and  **remote branches**. Local branches are simply that, local to your machine, and they can be linked to remote branches. Remote branches are located on the GitHub servers, and contain the changes that you push to them.

As mentioned before, you can interact with branches in many different ways. Below are the basics.

### Committing

When you make changes locally, they will be reflected in your local environment.


### Adding 

When you 


## Repositories


Repositories are the foundation of git. There are the 'hubs' of code that contain all of the code ch


