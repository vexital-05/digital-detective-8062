# MISSION 6 - Git and Github

## Task 6.1 - Understand the basic Git workflow

#### This task is completed and the steps done to do the same is shown in [this image](../evidence/mission-06/task6.1.png).

| Git Operation | What it does in your own words |
| --- | --- |
| Check repository status | This operation is done by using the `git status` command. It shows the unstaged and untracked files. It also shows which branch the current HEAD is located on and if the branch is up to date or not. |
| Stage selected changes | This operation is done by using the `git add` command. It starts tracking the file changes that are added by using the same command. |
| Create a commit | This operation is done by using the `git commit -m ""` command. This operation creates a version of main repository by which if anything goes wrong in the future, the user can just revert the codebase back to this version. |
| View commit history | This operation is done by using the `git log` command. It shows the entire commit history of the repository, i.e. all the versions of the repository along with its commit ID, which helps in switching to that particular ID if something goes wrong. |

--- 

## Task 6.2 - Create and use a branch

#### This task is completed and the steps done to do the same is shown in [this image](../evidence/mission-06/task6.2.png).

---

## Task 6.3 - Create a Pull Request

#### This task is completed and the Pull Request has been successfully created but has not been merged into the main branch as it was not yet instructed by the instructor to do so.

#### A branch can be defined as a parallel version of your code where you can add features to the code without affecting the main code. Pull request is an official request asking the maintainer of the repository to merge the code changes from your branch to the main branch within the same repository. This system is extremely useful and efficient when people work on the same project as it adds an extra developer which goes through the code and looks for bugs and edge cases where the logic of the code fails.

---

## Task 6.4 - Build your Git command glossary

| Git Operation | Git Command | One-line Explaination |
| --- | --- | --- |
| Initialize a repository | `git init` | Initializes a git repository on your local machine in the current working directory. |
| Check Status | `git status` | Shows the status of the current repository, which branch is the HEAD currently on and the unstaged and untracked files. |
| View History | `git log` | Shows the entire history of the repository, i.e. its commit history along with its IDs. |
| Create or list branches | `git branch` | This base command with the name as the argument will create a new branch without switching to the branch and using the base command with the `-l` attribute will list all the branches in your git repository. |
| Switch branches | `git switch` or `git checkout` | This will move your HEAD to the branch that will be inputted as an argument after either of the base commands. |
| Publish changes | `git push` | This command will publish all the changes done locally to the remote repository on Github. |
| Retrieve remote changes | `git pull` or `git fetch` | This command will retrieve all the remote changes made on the Github repository to the local Git repository and will either _overwrite_(`git pull`) or _not change_(`git fetch`) the current working code. |