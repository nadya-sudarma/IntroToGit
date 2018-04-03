# IntroToGit
Repository to use for Git/GitHub practice


## Install git

Follow the instructions found here:

**MAC**

https://www.atlassian.com/git/tutorials/install-git#mac-os-x​

**Windows**

https://www.atlassian.com/git/tutorials/install-git#windows


## Instructions

1. Organize into groups of 4-5
2. Choose a team leader to fork off of our public code repo:
	
https://github.com/cnoah/IntroToGit​	
​

3. Everyone else fork off of the repo created from step 2

All members of the group will now:

4. Clone from your personal repo

	• *Hint:* `git clone ....`

5. Setup upstream environment

	• *Hint:* `git remote ....`

6. Create a new branch (called "myDev") from your **master** branch

	• *Hint:* `git checkout ....`

7. Add your name to names.txt
8. Push your changes to your personal repo on Github
	
	• *Hint:* **P**aul **A**dores **C**uddly **P**uppies

9. All non-team leaders of the group should create a pull request to the team leader's repo on Github
10. Once members have completed step 9, the team leader should create a pull request to the main repo from step 2

**ALWAYS PUSH TO ORIGIN, _NEVER_ UPSTREAM**


## Reference
### Common Terms
| Term     | Definition |
|----------|------------|
| **Repository ("Repo")** | The database that stores the files | 
| **Working Directory** | Your local directory of files |
| **Revision** | The version that a specific files is on |
| **Branch** | A separatecopy of the code, where changes can be made independently from the main "trunk" |
| **Fork** | A copy of a repository | 
| **Upstream** | Typically the repo that you forked from |
| **Pull request ("PR")** | A request to merge changes from one branch to another. Can be between branches across different forks of a repo |


### Basic Commands
| Command      | Usage |
|--------------|-------|
| **`git clone <repo_url>`**| Clone a repository into a new local directory |
| **`git remote [-v add]`** | Your reference to online repositories. `-v` lists the reference name and corresponding link to the repository. `add <name> <repo_url>` adds a new reference to an online repository |
| **`git checkout [-b] <branch>`** | Switches to another branch on your local working copy. Adding the `-b` flag will create the branch if it doesn't exist and switch inside it |
| **`git status`** | Shows the working tree status (files with changes, files ready for commit, etc.) |
| **`git pull <repo_name> <repo_branch>`** | Fetch from and integrate with another repo or a local branch | 
| **`git add <file_name>`** | Adds a change in the working directory to the staging area |
| **`git commit –m "<message>"`** | Record changes to a repo |
| **`git push <repo_name> <branch>`** | Sends commits (code changes) to remote repo |
