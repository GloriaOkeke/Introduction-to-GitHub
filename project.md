# Introduction to GitHub
## Table of Content
### Introduction
### What is GitHub?
### Why GitHub?
### Git vs. GitHub
### GitHub Desktop vs. GitHub CLI
### Cloning: How To Clone on GitHub 
### Commit: How to Commit Changes on GitHub
### Pull Request; How to Create Pull Request
## Conclusion

## Introduction
Most of the cutting-edge technologies in the world are built by developers on GitHub. Whether visualizing data, building software, a new game, or writing about new technology, there's a whole system and set of tools on GitHub that helps you do it even better. 

This article covers everything you need to know about GitHub, GitHub Desktop, GitHub CLI, and how to carry out essential operations like Cloning, Commit, and Pull requests using GitHub CLI. 

## What is GitHub?
GitHub is a code hosting system for Git version control that allows people (mainly developers) to collaborate and work together on projects from any location in the world.

On GitHub, anyone can share their codes on projects, including website design or development, and build alongside millions of other developers.

GitHub is owned by Microsoft and is currently the world's largest host of source code.

## Why GitHub?
Developers, companies, and almost everyone working online use Git for some reasons:

- GitHub allows a large group of persons to work simultaneously on a single project, thus speeding up production.
- GitHub reduces the possibility of duplicate or conflicting work through various features and checks on the platform.
- Changes are not lost on GitHub; developers can quickly revert to previous project versions if needed.
- GitHub offers vital DevOps features that businesses and organizations of all scales required.
- Non-coders can use GitHub to create, edit, and update website content.

## Git vs. GitHub
You might mistake GitHub for Git and vice versa, but Git and GitHub do not mean the same thing.

**Git** means a distributed version control system (DVCS) for tracking changes in source code during software development.  

**GitHub** is a web platform that uses Git as its core technology and simplifies the overall flow that enables developers and users to work together. 

According to [GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-git-and-github/?ref=leftbar-rightbar), 

Git is:

- a software
- a command-line (CL) tool
- open-source licensed
- installed locally on the system
- focused on version control and code sharing
- maintained by Linux
- It was first launched in 2005 

While GitHub is: 
- a service
- a Graphical User Interface
- hosting service for Git repositories 
- hosted on the web
- focused on centralized source code hosting
- maintained by Microsoft
- It was first launched in 2008 

## GitHub Desktop vs. Github CLI
**GitHub Desktop** is a platform that enables you to connect with GitHub using a **GUI**(Graphical User Interface). With GitHub Desktop, you can complete most Git commands from the desktop, such as push, pull, and clone for remote repositories, committing changes and creating pull requests.

Conversely, **GitHub CLI** is an open-source tool that allows you to interact with GitHub from the **Command line** on your computer instead of the GUI. 
GitHub CLI enables push, commit, clone, pull requests, and some extra functionalities.

Though GitHub Desktop can be used for simple applications and some intermediate tasks, most people prefer GitHub CLI because of the extra features and efficiency. 

GitHub Desktop also requires a lengthy installation and set-up process, but almost every computer has a terminal that makes GitHub CLI easy to access.

There is much more power and flexibility when using the command line on various software technologies. 

**Now, let's move over to how to carry out various operations on GitHub, like Cloning, Committing changes, and Creating Pull Requests.** 

*We will be using the GitHub CLI for illustration.*

## Cloning: How To Clone on GitHub  
A clone is a full duplicate of a repository containing all logging and versions of files. Cloning is done to download an existing GitHub repository to a local computer. 

### Follow the Steps Below to Clone a GitHub Repository:
1. Open GitHub 
2. Navigate to the GitHub repository that you want to clone.
3. Click "Code" 
4. Copy the URL shown

![illustration](images/Screen%20Shot%202022-10-08%20at%2010.43.06%20AM.png)

5. Open “Terminal” 
6. Navigate to the particular directory where you want the cloned file to move.
7. Type *git clone {the URL you copied earlier}*
8. Tap “enter” on your keyboard to create your local clone.

![illustration](images/Screen%20Shot%202022-10-08%20at%2010.44.55%20AM.png)

*You successfully Cloned the GitHub Repository🚀*

## Commit: How to Commit Changes on GitHub
A commit is a change made to one or more files on a project. 
Adding commits on GitHub allows you to track progress and modifications as you work. Git regards each commit in a project as a "save point," where you can refer to it if there is a bug or want to make other adjustments.

Each commit has a corresponding commit message describing why a particular change was made.

### How to Commit Changes on GitHub
The steps here will guide you through the process of committing a change on GitHub. 

**Note:** it is advised you change the file branch and avoid working directly on the main branch before committing a change. This helps arrange different features in separate branches and secure the main branch from potential bugs.

### Steps:
1. Open the file (contactpage.html) on vscode.
2. Change the file branch by typing the command:
*git checkout -b {branchname}*

   **That done, continue to commit change:**

3. Go back to the file, and edit whatever you want; code, syntax, etc.
4. Type *git add .* on the terminal to stage changes
5. Type *git commit -m "commit message"* 
   
![illustration](images/Screen%20Shot%202022-10-08%20at%2011.20.41%20AM.png)

The message at the end of the commit should be concise and clearly describe the change you just made- perhaps you added a new feature or fixed a typo or bug. 

6. Type git push origin {branchname} to push the file back to GitHub.

*You successfully Committed a change🚀*

These changes will be made only to the “contactpage.html” file on the new branch you created in **step 2**.

## Pull Request; How to Create Pull Request
After committing a change, it’s time to make the pull request.

A pull request is a way to propose changes and request that the repository owner review, pull in, and merge your contribution into their branch. Making a pull request lets the owner review the code and ensure it won’t affect the original project before accepting it to the main branch. 
### Steps:
1. Click the “Compare & pull request” button on the repository you committed a change.

![illustration](images/Screen%20Shot%202022-10-08%20at%2011.32.43%20AM.png)

2. Check the changes and make sure they're what you want to submit.
3. Add a comment describing the change
4. Click "Create pull request."

![illustration](images/Screen%20Shot%202022-10-08%20at%2011.33.40%20AM.png)

*You successfully created a Pull Request🚀*

Once the change is approved, the pull request's source branch will automatically be merged into the main branch.

## The End
Here's a Quick Summary of all you learned in this article:
- Learned about GitHub and Why it is Popular
- Learned Git vs. GitHub and GitHub Desktop vs. GitHub CLI.
- How to clone, commit and push change using GitHub CLI
- How to create a simple pull request on GitHub.
