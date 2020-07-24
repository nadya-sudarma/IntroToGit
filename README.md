# IntroToGit
Repository to use for Git/GitHub practice


## Install git

Follow the instructions found here:

**MAC**

https://www.atlassian.com/git/tutorials/install-git#mac-os-x​

**Windows**

https://www.atlassian.com/git/tutorials/install-git#windows


## Instructions

1. Identify team leader
    * If nobody volunteers, then whoever's birthday was most recent!
2. Team leader forks master repository: https://github.com/cnoah/IntroToGit​	
3. Team members fork **team leader's** repository
4. Everyone:
    1. Clone your forked repo to your local computer
    2. Set up "upstream" reference (Hint: `git remote...`)
        1. Team leader - use https://github.com/cnoah/IntroToGit as "upstream"
        2. Team members - use your team leader's repo
    3. Check out your team's branch (Hint: `git checkout...`)
    4. Add your name to **names.txt**
    5. Push your local changes to your repo
5. Team members create a pull request from their repo to their team leader's repo, in the team branch
6. Team leaders merge pull request, after any merge conflicts are resolved
7. Once all team member PRs are merged into team leader repo, team leader creates PR to their upstream (cnoah/IntroToGit)

**ALWAYS PUSH TO ORIGIN, _NEVER_ UPSTREAM**


## Reference
### Common Terms
| Term     | Definition |
|----------|------------|
| **Repository ("Repo")** | The database that stores the files | 
| **Working Directory** | Your local directory of files |
| **Revision** | The version that a specific files is on |
| **Branch** | A separate copy of the code, where changes can be made independently from the main "trunk" |
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
| **`git pull <repo_name> <repo_branch>`** | Fetch from remote repo (usually "upstream") and integrate with local working directory | 
| **`git add <file_name>`** | Adds a change in the working directory to the staging area |
| **`git commit –m "<message>"`** | Record changes to a repo |
| **`git push <repo_name> <branch>`** | Sends commits (code changes) to remote repo |
