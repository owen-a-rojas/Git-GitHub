# Git&GitHub

## What is Git?

__Git is a distributed version control system (DVCS) that is widely used for tracking changes in source code during software development.__


## Some key concepts and features of Git:

+ ***Version Control System (VCS)*** Git allows developers to track changes in their codebase over time. It records changes to a repository, which can include source code, configuration files, and other project assets.

    + ***Distributed*** Git is a distributed version control system, which means that every developer has a complete copy of the entire repository on their local machine. This makes it possible for developers to work offline and independently before syncing their changes with a central repository.

    + ***Repositories*** A Git repository is a collection of files and folders along with the entire history of changes made to those files. There can be a remote repository (on a server) and one or more local repositories (on individual developers' machines).

+ ***Commits*** A commit in Git represents a snapshot of the project at a specific point in time. Each commit has a unique identifier, and it contains information about the changes made, such as additions, deletions, and modifications.


+ ***Branching*** Git allows developers to create branches, which are essentially separate lines of development. Branches are useful for isolating features, bug fixes, or experiments without affecting the main codebase. Branches can be merged back into the main branch when the changes are ready.

+ ***Merging*** Is the process of combining changes from different branches. Git provides tools for automatic merging, but conflicts may arise if changes made in different branches overlap.

+ ***Pull Requests*** In collaborative development environments, developers often use pull requests (or merge requests) to propose changes and discuss them before merging into the main branch. This allows for code review and collaboration.


## Steps to follow when use Git

```
Git init (Is used to initialize a new Git repository.)
```
```
Git config (Is used to configure Git settings.)

Setting User Information

git config user.name "Your Name"
git config user.email "your.email@example.com"   
```
```
Git remote add origin (Is used to associate a remote repository with your local Git repository. The term "origin" is often used as a default remote repository name, but you can choose a different name if you prefer.)

git remote add origin <remote_repository_url>

You can verify that the remote is correctly set by using:
git remote -v

Push Your Changes
After adding the remote, you can push your local commits to the remote repository:
git push -u origin master
```
```
Git add (Is used to stage changes for the next commit in a Git repository.)

1.Add All Changes:
git add .

2.Add Specific File:
git add <filename>

3.Add All Changes in a Directory:
git add directory/

4.Interactive Mode:
git add -i (This command starts interactive mode, allowing you to selectively stage changes. It provides a menu with options to stage or unstage changes interactively.)

5.Add With Patch:
git add -p (This command interactively lets you stage changes in a patch-by-patch manner. You can choose which parts of a file you want to stage.)

6.Add All Untracked Files:
git add -A (This command stages all modifications, deletions, and additions, including untracked files.)

After using git add to stage changes, you'll typically follow it up with a git commit command to save the staged changes to the version history. 

git commit -m "Your commit message"
```
```
Git Clone (Is used to create a copy of a remote Git repository on your local machine. It's commonly used when you want to start working on an existing project or collaborate with others.)

Clone the repository:
git clone <repository_url>

If you want to clone into a specific directory, you can provide the directory name as the second argument:
git clone <repository_url> <directory_name>

You can use Git commands to work on the project, make changes, and collaborate with others. For example:

git pull origin master: Fetches changes from the remote repository to your local repository.

git push origin master: Pushes your local changes to the remote repository.

git branch: Lists available branches.

git branch <branch_name>: Create new branch.

git branch -m: Rename the branch.

git branch -d: Delete a branch.

git branch -a: View all branches (Local and Remote.)

git checkout <branch_name>: Switches to a specific branch.
```


## What is GitHub

__GitHub is an online software development platform. It's used for storing, tracking, and collaborating on software projects.__

## Key features and aspects of GitHub include:

+ ***Git Repository Hosting:*** GitHub allows users to host their Git repositories in the cloud. This means that developers can push their code to a central repository on GitHub, making it accessible to others.

+ ***Collaboration:*** GitHub provides tools for collaboration, allowing multiple developers to work together on the same project. Developers can fork repositories to create their own copies, make changes, and then propose those changes back to the original repository through pull requests.

+ ***Pull Requests:*** Pull requests (or merge requests) are a mechanism for proposing and discussing changes before merging them into the main branch. This allows for code review and collaboration among team members.

+ ***Code Review:*** GitHub has built-in tools for reviewing code changes. Developers can comment on specific lines of code, suggest improvements, and discuss changes within the context of a pull request.

+ ***Issue Tracking:*** GitHub includes a robust issue tracking system. Issues can be used to report bugs, suggest features, or discuss tasks. Issues can be linked to specific commits and branches, providing context for discussions.

+ ***Wiki and Documentation:*** GitHub allows users to create wikis and documentation associated with their projects. This is useful for maintaining project documentation, FAQs, and other important information.

+ ***Actions and Workflows:*** GitHub Actions enables automation of workflows, such as running tests, building and deploying applications, and more. Workflows can be defined using YAML files and triggered by various events, such as code pushes or pull requests.

+ ***Community and Social Features:** GitHub has a social aspect, with features like following other developers, starring repositories, and contributing to open-source projects. It fosters a sense of community and collaboration.


![Git&GitHub](https://miro.medium.com/v2/resize:fit:1400/0*mnBPahCuD9Xf-grZ)