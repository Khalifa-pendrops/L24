# Learnable_24_assignment_on_git

# Version Control and Git Basics
This README introduces the concepts of version control, explains the differences between Git and GitHub, and covers essential Git commands with simple examples. It is designed to help you understand version control and Git workflow.


## What is Version Control?

Version control is an essencial programming technique that tracks changes made to files over time, allowing you to collaborate with others more effectively by merging changes, revert to earlier versions of your code if necessary, understand who made what changes to the file, when, how and why. It helps for software development, documentation, and any project where file changes need to be made and tracked.



## Difference Between Git and GitHub

Git: Git is a CL (command-line) tool that is installed locally. It helps to tracks changes in files and allows multiple people to work on a project simultaneously. 
GitHub: A cloud-based platform that hosts Git repositories, making it easier to collaborate, manage, and share projects online. It provides several features like issue tracking, pull requests, project management, etc.


## Alternatives to GitHub

There are three common alternatives to GitHub, and they include;
1. GitLab: Offers Git repository hosting, CI/CD pipelines, and integrated DevOps tools.
2. Bitbucket: Focuses on integration with Atlassian tools like Jira and Trello, commonly used in teams.
3. SourceForge: An older platform for hosting and managing open-source projects, with Git support.


## Difference Between `git fetch` and `git pull`

`git fetch`: this means to download changes from the remote repository but does not merge them into your local branch. It keeps your local branch untouched until you explicitly merge. Command example:

    git fetch origin


`git pull`: this downloads changes from the remote repository and automatically merges them into your local branch. Command example:  
 
    git pull origin main



## Git Rebase Explained
Git Rebase: this piles up, moves or applies your commits on top of another branch’s commits, creating a linear history.  
You can use it to clean up your commit history or integrate changes from one branch into another without creating a merge commit.


### Git rebase Commands:
 Enter the following commands:

   git checkout (your-branch)

   git rebase main


## Git Cherry-Pick Explained
Git Cherry-Pick: this lets you apply specific commits from one branch to another.
You can use it to pick certain changes without merging an entire branch.

### Git cherry-pick commands:
Enter the following commands:

1. identify the commit hash
    git log
    
2. Cherry-pick the commit
    git cherry-pick (commit-hash)