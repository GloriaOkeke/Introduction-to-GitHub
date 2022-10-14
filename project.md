# Introduction to GitHub
## Table of Content
### Introduction
### What is GitHub?
### Why GitHub?
### Git vs. GitHub
### GitHub Desktop vs. GitHub CLI
### Cloning: How To Clone on GitHub 
### Commit: How to Commit Changes on GitHub
### Pull Request: How to Create Pull Request
## Conclusion

## Introduction
With over [83 million](https://www.linkedin.com/company/github) users, GitHub is one of the best platforms to comfortably share ideas, build with other developers and bring dream technologies to life. Whether visualizing data, building software, a new game, or writing about new technology, there's a whole system and set of tools on GitHub that helps you do it even better. 

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

According to [GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-git-and-github/?ref=leftbar-rightbar):

| Git |   GitHub|
|---|---|
| Git is a software package  | GitHub is a service  |
| Git is a command-line (CL) tool  | GitHub is a Graphical User Interface (GUI)  |
| Git is open-source licensed  |  GitHub is a hosting service for Git repositories   |
| Git is setup locally on the system  | GitHub is hosted online  |
| Git is focused on version control and code sharing | GitHub is focused on centralized source code hosting  |
| Git is maintained by Linux | GitHub is maintained by Microsoft  |
| Git was first launched in 2005   | GitHub was first launched in 2008   |

## GitHub Desktop vs. Github CLI
GitHub Desktop and GitHub CLI are both tools that enable interaction and collaboration on GitHub. With these tools, you can complete operations, such as pushing, pulling, and cloning for remote repositories, committing changes, and creating pull requests.

There is much more power and flexibility when using these tools on building various software technologies. 

However, there are significant differences between the both, which are as follows:

|  GitHub Desktop | GitHub CLI  |
|---|---|
|GitHub Desktop enables interaction with GitHub using a **GUI** (Graphical User Interface)   | GitHub CLI enables interaction with GitHub from the **Command line**  |
| GitHub Desktop is easier to navigate  | GitHub CLI is advanced and require some technical knowledge |
| GitHub Desktop may not allow advanced functionalities like rebases | GitHub CLI allows advanced functionalities like rebases|
| GitHub Desktop can be used on building simple applications  | GitHub CLI is preferred on building higher applications |
| GitHub Desktop always requires installation and set-up process | GitHub CLI does not always require installation and set-up  |

Most people prefer GitHub CLI because of the extra features and efficiency. 

## How to Carry out various Operations on GitHub

*We will be using the GitHub CLI for illustration.*

## I. Cloning  
A clone is a full duplicate of a repository containing all logging and versions of files. Cloning is done to download an existing GitHub repository to a local computer. 

### How To Clone on GitHub

#### Steps:
1. Open the GitHub website {[github.com](https://github.com/)} 
2. Login to your GitHub profile
3. Navigate to *"your repositories"*

   ![illustration](images/Screen%20Shot%202022-10-14%20at%2012.32.29%20PM.png)

4. Click on the GitHub repository that you want to clone.

   ![illustration](images/Screen%20Shot%202022-10-14%20at%2012.32.56%20PM.png)

5. Once the repository opens, Click "Code" button on green
6. Copy the URL shown by clicking on the copy icon at bottom-right

   ![illustration](images/Screen%20Shot%202022-10-14%20at%2012.03.51%20PM.png)

7. Return to your Computer's home screen
8. Open **“Terminal”** (if you're using Mac) or Open **"PowerShell"** (if you're using Windows)

   To open the Terminal on Mac:

   i. Click the **search icon** at the top-right corner of your home screen
   
   ii. Search for "Terminal" and select to open

   ![illustration](images/Screen%20Shot%202022-10-14%20at%203.24.10%20PM.png)

   iii. The terminal should be opened this way:

      ![illustration](images/Screen%20Shot%202022-10-14%20at%203.31.44%20PM.png)


9.  Type the command `cd` to navigate to the particular folder where you want the cloned file to move.
    
    For instance: `cd documents
`

    ![illustration](images/Screen%20Shot%202022-10-14%20at%2012.07.10%20PM.png)

10.  On the terminal, type: `git clone {the URL you copied earlier}` 

     For instance: 

         git clone https://github.com/GloriaOkeke/demo-repository.git

11.   Tap “enter” on your keyboard to create your local clone.   
   
       The GitHub repository will automatically be downloaded (cloned) to your computer and should appear this way:

       ![illustration](images/Screen%20Shot%202022-10-14%20at%2012.13.22%20PM.png)

*You successfully Cloned the GitHub Repository🚀*

## II. Commit
A commit is a change made to one or more files on a project. 
Adding commits on GitHub allows you to track progress and modifications as you work. Git regards each commit in a project as a "save point," where you can refer to it if there is a bug or want to make other adjustments.

Each commit has a corresponding commit message describing why a particular change was made.

### How to Commit Changes on GitHub
The steps here will guide you through the process of committing a change on GitHub. 

*Note:* Before making commits, you should first change the file branch and avoid working directly on the main branch of the repository. This helps arrange different features in separate branches and secure the main branch from potential bugs.

#### Steps:
1. Open your vscode

   ![illustration](images/Screen%20Shot%202022-10-14%20at%2012.55.12%20PM.png)

2. Next, Click "Open", and select the GitHub repository you cloned earlier.
   
3. Open the terminal inside vscode by clicking "View" at the top bar and selecting "Terminal"
   ![illustration](images/Screen%20Shot%202022-10-14%20at%2012.58.28%20PM.png)

   The terminal opens at the bottom page on vscode.
   
   ![illustration](images/Screen%20Shot%202022-10-14%20at%201.08.52%20PM.png)

4. Next, on the terminal, type the command:
`git checkout -b {branchname}` to change file branch

   For instance: 
   
   `git checkout -newbranch`

5. Go up to the particular file, and make the required edits.
6. Save the edits by pressing cmd+s (for Mac) or control+s (for Windows)

   ![illustration](images/Screen%20Shot%202022-10-14%20at%201.40.23%20PM.png)

7. Go down to the terminal on the vscode folder and type `git add .` to stage the changes you just made

8. Type `git commit -m "commit message"` 
   
   For instance:

   `git commit -m "edited contact page css"`
 

   The message at the end of the commit should be concise and clearly describe the change you just made- perhaps you edited the contact page css, added a new feature or fixed a typo or bug.

   Also, ensure to enclose the commit message with the quotation marks. The step may not work out without this syntax.

9.  Type `git push origin {branchname}` to push the file back to GitHub.

    For instance: 

    `git push origin newbranch`

10.  Return to GitHub repository on the website. 
   
     If the commit was successful, you should see something like this image below: 
 
     ![illustration](images/Screen%20Shot%202022-10-14%20at%201.53.09%20PM.png)

     *You successfully Committed a change on the GitHub repository🚀*

## Pull Request
After committing a change, it’s time to make the pull request.

A pull request is a way to propose changes and request that the repository owner review, pull in, and merge your contribution into their branch. Making a pull request lets the owner review the code and ensure it won’t affect the original project before accepting it to the main branch. 

### How to Create Pull Request
#### Steps:
1. On the GitHub repository, Click the “Compare & pull request” button that shows after you committed a change

   ![illustration](images/Screen%20Shot%202022-10-14%20at%202.08.33%20PM.png)

2. Next, check the changes and make sure they're what you committed earlier
3. Leave a comment describing the change
4. Click "Create pull request."

   ![illustration](images/Screen%20Shot%202022-10-14%20at%202.12.04%20PM.png)

   If the pull request was successful, you should see something like this image below: 
   ![illustration](images/Screen%20Shot%202022-10-14%20at%202.16.46%20PM.png)

   *You successfully created a Pull Request on the GitHub repository🚀*

Once the change is approved, the pull request's source branch will automatically be merged into the main branch.

## Conclusion
Learning GitHub as a developer is super important because it helps you network with millions of other developers, contribute to open-source projects, improve coding skills and build a strong portfolio in software development. 

With the detailed article, you now understand what GitHub means and how to use it for various operations.
