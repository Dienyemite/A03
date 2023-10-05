# A02

## Git Tutorial
### Step 1- Install GIT
You can download **GIT** for free from [here](https://git-scm.com).

### Step 2-Check out for GIT Installation
Once you've downloaded GIT, open a command shell and use the commands:
```
git --version ###enter this line
git version X.Y.Z.osbrand.A ###this should be the return line
```
### Step 3-Enter Credentials into GIT
User info is required for input within GIT, Furthermore, commits from GIT are useful in maintaining structure and clarity. The following commands allow you to input your information:
```
###substitute your own information
git config --global user.name "sm527"
git config --global user.email "sm527@njit.edu"
```
> `global` sets the username and e-mail for every **repository** within your system, and if you don't want it for every instance then erase from the command  current repository only.
### Step 4-New Directory
Create a new directory for the project.
```
mkdir projectName ###makes new director projectName
cd projectName ###change working directory into projectName
```
### Step 5- Initialize
First GIT repo that the initialization will make possible. GIT keeps track of changes to this folder for changes and keep track of within a hidden folder.
```
git init
Intialized empty Git repository in /Users/user/projectName/.git/
```
Through all the steps so far, the first local repo has been created.

## GitHub Tutorial

### Step 1-Make Account
Go to [GitHub](github.com) and create an account for **GitHub**.
![Account Creation](https://www.w3schools.com/git/img_githup_sign_up.png)

### Step 2-Make Repository
Click the plus button dropdown around the upper righthand corner of the site of the navigation bar. Click the button that says `New repository`.
![Repo Creation](https://www.w3schools.com/git/img_github_new_repo.png)
Fill in info for the repository. This one is for a W3 Schools [tutorial](https://www.w3schools.com/git/git_remote_getstarted.asp?remote=github). Tutorials henceforth will reference to W3 school for the steps.
![Repo Info](https://www.w3schools.com/git/img_github_new_repo_create.png)

### Step 3-Pushing the repo
The repo which has been created will be **pushed** onto a new Github account. With both conbination of GitHub username and GitHub repo, it will be joined into an URL such as.
> https://github.com/cc756/A03.git
This URL will be copied and used inside the command line.
```
git remote add origin https://github.com/cc756/A03.git
```
`git remote add origin URL` specifies that you are adding a **remote** repository, with the specified `URL`, as an `origin` to your local Git repo.
The github will be pushed, which will execute a notification to authenticate.

**PUSH**
```
git push --set-upstream origin master
Enumerating objects: 22, done.
Counting objects: 100% (22/22), done.
Delta compression using up to 16 threads
Compressing objects: 100% (22/22), done.
Writing objects: 100% (22/22), 92.96 KiB | 23.24 MiB/s, done.
Total 22 (delta 11), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (11/11), done.
To https://github.com/cc756/A03.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
```
### Step 5 - Push connection
Go back to your repository on GitHub to see if the **merge** happened or if there was a **merge conflict**.
![Successful Push](https://www.w3schools.com/git/img_github_merged.png)




## Glossary
**Branch**: New or separate version of a main repository, which lets developers edit the code without effecting the main branch. Allows seamless mulititasking with different teams because of separate versions of the same repo.

**Clone**: `git clone` local copy of a project that exists remotely. The git clone possesses all the files, history, and branches of a project.

**Commit**: `git commit` Takes and saves a snapshot to a project's history and finalizes the change-tracking process. In short, a commit functions like taking a photo. Anything that's been staged with `git add` will become a part of the snapshot with `git commit`.

**Fetch**: allows users to download files and changes from the remote to their local repository. Generally good practice to run `git fetch` before you start

**GIT**: a version control system tracks the history of changes as people and teams collaborate on projects together. Distributed version control systems don't need a constant connection to a central repository. Git is the most popular distributed version control system. Also used to start commands when using Git directly from the command line

**Github**: a website that has Git repositories and provides developers with tools to ship better code through command line features, issues (threaded discussions), pull requests, code review, or the use of a collection of free and for-purchase apps in the GitHub Marketplace.

**Merge**: `git merge` joins two or more branches together and incorporates the changes from the named commits into the current branch the user is working in.

**Merge Conflict**: when two branches have commits that conflict with each other and you attempt to merge them, Git needs to decide which commits to actually use in the final merge. This is usually done automaticaly but sometimes Git needs your help.

**Push**: `git push` updates the remote repository with commits made locally within a branch.

**Pull**: `git pull` updates the local line of development with updates from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in their local environment.

**Remote**: a repository that is hosted on a server that is accessible to all team members. Code hosting services such as Github can serve as storage for remote repositories.

**Repository**: a collection of files that compiled together as a project, alongside other commit/file revision history of the project

## References
<details><summary>Click for references</summary> 
<p>
  
  - [Jet Brains](https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html)
  - [GitHub Docs](https://docs.github.com/en)
  - [W3 Schools Git Tutorial](https://www.w3schools.com/git/)
  - Past classes
  
</p>
</details>
