
1. Git Configuration Commands
git config --global user.name
Syntax:
git config --global user.name "Your Name"
Purpose:
Sets the username used in Git commits.
Example:
git config --global user.name "Pallavi"
git config --global user.email
Syntax:
git config --global user.email "[your_email@example.com](mailto:your_email@example.com)"
Purpose:
Sets the email address used in Git commits.
Example:
git config --global user.email "[pallavi@gmail.com](mailto:pallavi@gmail.com)"
git config --list
Syntax:
git config --list
Purpose:
Displays all Git configuration settings.
Example:
git config --list
git config --unset
Syntax:
git config --unset user.name
Purpose:
Removes a Git configuration value.
Example:
git config --unset user.name
2. Repository Setup Commands
git init
Syntax:
git init
Purpose:
Initializes a new Git repository.
Example:
git init
git clone
Syntax:
git clone <repository-url>
Purpose:
Creates a local copy of a remote repository.
Example:
git clone https://github.com/octocat/Hello-World.git
git clone --branch
Syntax:
git clone --branch <branch-name> <repository-url>
Purpose:
Clones a repository and checks out a specific branch.
Example:
git clone --branch main https://github.com/octocat/Hello-World.git
git clone --depth
Syntax:
git clone --depth 1 <repository-url>
Purpose:
Clones only the latest commit history.
Example:
git clone --depth 1 https://github.com/octocat/Hello-World.git
3. Repository Status & Inspection
git status
Syntax:
git status
Purpose:
Shows the current state of the working directory.
Example:
git status
git log
Syntax:
git log
Purpose:
Displays commit history.
Example:
git log
git log --oneline
Syntax:
git log --oneline
Purpose:
Shows commit history in compact form.
Example:
git log --oneline
git log --graph
Syntax:
git log --graph
Purpose:
Displays commit history as a graph.
Example:
git log --graph
Screenshot Proof:
(Add screenshot)
git show
Syntax:
git show <commit-id>
Purpose:
Displays details of a specific commit.
Example:
git show HEAD
git diff
Syntax:
git diff
Purpose:
Shows changes between commits or files.
Example:
git diff
git diff --staged
Syntax:
git diff --staged
Purpose:
Shows staged changes.
Example:
git diff --staged
git blame
Syntax:
git blame <file>
Purpose:
Shows who modified each line of a file.
Example:
git blame file.txt
git reflog
Syntax:
git reflog
Purpose:
Shows reference history of HEAD.
Example:
git reflog
git shortlog
Syntax:
git shortlog
Purpose:
Displays commit summary by author.
Example:
git shortlog
4. File Tracking Commands
git add
Syntax:
git add <file-name>
Purpose:
Adds a file to staging area.
Example:
git add file.txt
git add .
Syntax:
git add .
Purpose:
Adds all files to staging area.
Example:
git add .
git add -p
Syntax:
git add -p
Purpose:
Adds changes interactively.
Example:
git add -p
git restore
Syntax:
git restore <file>
Purpose:
Restores a file from the repository.
Example:
git restore file.txt
git restore --staged
Syntax:
git restore --staged <file>
Purpose:
Unstages a staged file.
Example:
git restore --staged file.txt
git rm
Syntax:
git rm <file>
Purpose:
Deletes a file from repository.
Example:
git rm file.txt
git mv
Syntax:
git mv oldname.txt newname.txt
Purpose:
Renames a file.
Example:
git mv old.txt new.txt
5. Commit Commands
git commit
Syntax:
git commit
Purpose:
Records staged changes.
Example:
git commit
git commit -m
Syntax:
git commit -m "message"
Purpose:
Commits changes with a message.
Example:
git commit -m "Added git commands practice"
git commit --amend
Syntax:
git commit --amend
Purpose:
Modifies the last commit.
Example:
git commit --amend
git commit --no-edit
Syntax:
git commit --no-edit
Purpose:
Amends commit without editing message.
Example:
git commit --no-edit
6. Branch Management Commands
git branch
Syntax:
git branch
Purpose:
Lists branches in repository.
Example:
git branch
git branch -a
Syntax:
git branch -a
Purpose:
Lists all local and remote branches.
Example:
git branch -a
git branch -d
Syntax:
git branch -d <branch-name>
Purpose:
Deletes a branch.
Example:
git branch -d feature
git checkout
Syntax:
git checkout <branch-name>
Purpose:
Switches to another branch.
Example:
git checkout main
git checkout -b
Syntax:
git checkout -b <branch-name>
Purpose:
Creates and switches to new branch.
Example:
git checkout -b new-feature
git switch
Syntax:
git switch <branch-name>
Purpose:
Switches branch.
Example:
git switch main
git switch -c
Syntax:
git switch -c <branch-name>
Purpose:
Creates and switches branch.
Example:
git switch -c test-branch
7. Merge Commands
git merge
Syntax:
git merge <branch-name>
Purpose:
Merges another branch into current branch.
Example:
git merge feature
git merge --no-ff
Syntax:
git merge --no-ff <branch-name>
Purpose:
Creates merge commit even if fast-forward possible.
Example:
git merge --no-ff feature
8. Remote Repository Commands
git remote
Syntax:
git remote
Purpose:
Lists remote repositories.
Example:
git remote
git remote -v
Syntax:
git remote -v
Purpose:
Shows remote repository URLs.
Example:
git remote -v
git remote add
Syntax:
git remote add origin <repo-url>
Purpose:
Adds remote repository.
Example:
git remote add origin https://github.com/user/repo.git
git remote remove
Syntax:
git remote remove origin
Purpose:
Removes remote repository.
Example:
git remote remove origin
git fetch
Syntax:
git fetch
Purpose:
Downloads commits from remote repository.
Example:
git fetch
git fetch --all
Syntax:
git fetch --all
Purpose:
Fetches updates from all remotes.
Example:
git fetch --all
git pull
Syntax:
git pull
Purpose:
Fetches and merges remote changes.
Example:
git pull
git pull --rebase
Syntax:
git pull --rebase
Purpose:
Fetches and rebases local commits.
Example:
git pull --rebase
git push
Syntax:
git push
Purpose:
Uploads local commits to remote repository.
Example:
git push
git push -u origin branch-name
Syntax:
git push -u origin branch-name
Purpose:
Pushes branch and sets upstream tracking.
Example:
git push -u origin main
git push --force
Syntax:
git push --force
Purpose:
Force pushes commits to remote repository.
Example:
git push --force
8. Remote Repository Commands
git remote
Syntax:
git remote
Purpose:
Lists all remote repositories connected to the local repository.
Example:
git remote
git remote -v
Syntax:
git remote -v
Purpose:
Displays remote repository names along with their URLs.
Example:
git remote -v
git remote add
Syntax:
git remote add origin <repository-url>
Purpose:
Adds a new remote repository to the local repository.
Example:
git remote add origin https://github.com/user/repository.git
git remote remove
Syntax:
git remote remove origin
Purpose:
Removes a remote repository from the local repository.
Example:
git remote remove origin
git fetch
Syntax:
git fetch
Purpose:
Downloads changes from the remote repository without merging them.
Example:
git fetch
git fetch --all
Syntax:
git fetch --all
Purpose:
Fetches updates from all configured remote repositories.
Example:
git fetch --all
git pull
Syntax:
git pull
Purpose:
Fetches changes from a remote repository and merges them into the current branch.
Example:
git pull origin main
Screenshot Proof:
(Add screenshot)
git pull --rebase
Syntax:
git pull --rebase
Purpose:
Fetches changes from the remote repository and rebases local commits on top of them.
Example:
git pull --rebase origin main
git push
Syntax:
git push
Purpose:
Uploads local commits to the remote repository.
Example:
git push origin main
git push -u origin branch-name
Syntax:
git push -u origin branch-name
Purpose:
Pushes a branch to the remote repository and sets it as the upstream branch.
Example:
git push -u origin main
git push --force
Syntax:
git push --force
Purpose:
Force pushes commits to the remote repository, overwriting remote history.
Example:
git push --force
