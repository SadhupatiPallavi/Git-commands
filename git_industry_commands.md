# Industry Level Git Commands Practice

---

1. Git Configuration Commands

git config --global user.name

Syntax:
git config --global user.name "Your Name"

Purpose:
Sets the username used in Git commits.

Example:
git config --global user.name "Pallavi"

Screenshot Proof:
(Add screenshot)

---

git config --global user.email

Syntax:
git config --global user.email "[your_email@example.com](mailto:your_email@example.com)"

Purpose:
Sets the email address used in Git commits.

Example:
git config --global user.email "[pallavi@gmail.com](mailto:pallavi@gmail.com)"

Screenshot Proof:
(Add screenshot)

---

git config --list

Syntax:
git config --list

Purpose:
Displays all Git configuration settings.

Example:
git config --list

Screenshot Proof:
(Add screenshot)

---

git config --unset

Syntax:
git config --unset user.name

Purpose:
Removes a Git configuration value.

Example:
git config --unset user.name

Screenshot Proof:
(Add screenshot)

---

2. Repository Setup Commands

git init

Syntax:
git init

Purpose:
Initializes a new Git repository.

Example:
git init

Screenshot Proof:
(Add screenshot)

---

git clone

Syntax:
git clone <repository-url>

Purpose:
Creates a local copy of a remote repository.

Example:
git clone https://github.com/octocat/Hello-World.git

Screenshot Proof:
(Add screenshot)

---

git clone --branch

Syntax:
git clone --branch <branch-name> <repository-url>

Purpose:
Clones a repository and checks out a specific branch.

Example:
git clone --branch main https://github.com/octocat/Hello-World.git

Screenshot Proof:
(Add screenshot)

---

git clone --depth

Syntax:
git clone --depth 1 <repository-url>

Purpose:
Clones only the latest commit history.

Example:
git clone --depth 1 https://github.com/octocat/Hello-World.git

Screenshot Proof:
(Add screenshot)

---

3. Repository Status & Inspection

git status

Syntax:
git status

Purpose:
Shows the current state of the working directory.

Example:
git status

Screenshot Proof:
(Add screenshot)

---

git log

Syntax:
git log

Purpose:
Displays commit history.

Example:
git log

Screenshot Proof:
(Add screenshot)

---

git log --oneline

Syntax:
git log --oneline

Purpose:
Shows commit history in compact form.

Example:
git log --oneline

Screenshot Proof:
(Add screenshot)

---

git log --graph

Syntax:
git log --graph

Purpose:
Displays commit history as a graph.

Example:
git log --graph

Screenshot Proof:
(Add screenshot)

---

git show

Syntax:
git show <commit-id>

Purpose:
Displays details of a specific commit.

Example:
git show HEAD

Screenshot Proof:
(Add screenshot)

---

git diff

Syntax:
git diff

Purpose:
Shows changes between commits or files.

Example:
git diff

Screenshot Proof:
(Add screenshot)

---

git diff --staged

Syntax:
git diff --staged

Purpose:
Shows staged changes.

Example:
git diff --staged

Screenshot Proof:
(Add screenshot)

---

git blame

Syntax:
git blame <file>

Purpose:
Shows who modified each line of a file.

Example:
git blame file.txt

Screenshot Proof:
(Add screenshot)

---

git reflog

Syntax:
git reflog

Purpose:
Shows reference history of HEAD.

Example:
git reflog

Screenshot Proof:
(Add screenshot)

---

git shortlog

Syntax:
git shortlog

Purpose:
Displays commit summary by author.

Example:
git shortlog

Screenshot Proof:
(Add screenshot)

---

4. File Tracking Commands

git add

Syntax:
git add <file-name>

Purpose:
Adds a file to staging area.

Example:
git add file.txt

Screenshot Proof:
(Add screenshot)

---

git add .

Syntax:
git add .

Purpose:
Adds all files to staging area.

Example:
git add .

Screenshot Proof:
(Add screenshot)

---

git add -p

Syntax:
git add -p

Purpose:
Adds changes interactively.

Example:
git add -p

Screenshot Proof:
(Add screenshot)

---

git restore

Syntax:
git restore <file>

Purpose:
Restores a file from the repository.

Example:
git restore file.txt

Screenshot Proof:
(Add screenshot)

---

git restore --staged

Syntax:
git restore --staged <file>

Purpose:
Unstages a staged file.

Example:
git restore --staged file.txt

Screenshot Proof:
(Add screenshot)

---

git rm

Syntax:
git rm <file>

Purpose:
Deletes a file from repository.

Example:
git rm file.txt

Screenshot Proof:
(Add screenshot)

---

git mv

Syntax:
git mv oldname.txt newname.txt

Purpose:
Renames a file.

Example:
git mv old.txt new.txt

Screenshot Proof:
(Add screenshot)

---

5. Commit Commands

git commit

Syntax:
git commit

Purpose:
Records staged changes.

Example:
git commit

Screenshot Proof:
(Add screenshot)

---

git commit -m

Syntax:
git commit -m "message"

Purpose:
Commits changes with a message.

Example:
git commit -m "Added git commands practice"

Screenshot Proof:
(Add screenshot)

---

git commit --amend

Syntax:
git commit --amend

Purpose:
Modifies the last commit.

Example:
git commit --amend

Screenshot Proof:
(Add screenshot)

---

git commit --no-edit

Syntax:
git commit --no-edit

Purpose:
Amends commit without editing message.

Example:
git commit --no-edit

Screenshot Proof:
(Add screenshot)

---

6. Branch Management Commands

git branch

Syntax:
git branch

Purpose:
Lists branches in repository.

Example:
git branch

Screenshot Proof:
(Add screenshot)

---

git branch -a

Syntax:
git branch -a

Purpose:
Lists all local and remote branches.

Example:
git branch -a

Screenshot Proof:
(Add screenshot)

---

git branch -d

Syntax:
git branch -d <branch-name>

Purpose:
Deletes a branch.

Example:
git branch -d feature

Screenshot Proof:
(Add screenshot)

---

git checkout

Syntax:
git checkout <branch-name>

Purpose:
Switches to another branch.

Example:
git checkout main

Screenshot Proof:
(Add screenshot)

---

git checkout -b

Syntax:
git checkout -b <branch-name>

Purpose:
Creates and switches to new branch.

Example:
git checkout -b new-feature

Screenshot Proof:
(Add screenshot)

---

git switch

Syntax:
git switch <branch-name>

Purpose:
Switches branch.

Example:
git switch main

Screenshot Proof:
(Add screenshot)

---

git switch -c

Syntax:
git switch -c <branch-name>

Purpose:
Creates and switches branch.

Example:
git switch -c test-branch

Screenshot Proof:
(Add screenshot)

---

7. Merge Commands

git merge

Syntax:
git merge <branch-name>

Purpose:
Merges another branch into current branch.

Example:
git merge feature

Screenshot Proof:
(Add screenshot)

---

git merge --no-ff

Syntax:
git merge --no-ff <branch-name>

Purpose:
Creates merge commit even if fast-forward possible.

Example:
git merge --no-ff feature

Screenshot Proof:
(Add screenshot)

---

8. Remote Repository Commands

git remote

Syntax:
git remote

Purpose:
Lists remote repositories.

Example:
git remote

Screenshot Proof:
(Add screenshot)

---

git remote -v

Syntax:
git remote -v

Purpose:
Shows remote repository URLs.

Example:
git remote -v

Screenshot Proof:
(Add screenshot)

---

git remote add

Syntax:
git remote add origin <repo-url>

Purpose:
Adds remote repository.

Example:
git remote add origin https://github.com/user/repo.git

Screenshot Proof:
(Add screenshot)

---

git remote remove

Syntax:
git remote remove origin

Purpose:
Removes remote repository.

Example:
git remote remove origin

Screenshot Proof:
(Add screenshot)

---

git fetch

Syntax:
git fetch

Purpose:
Downloads commits from remote repository.

Example:
git fetch

Screenshot Proof:
(Add screenshot)

---

git fetch --all

Syntax:
git fetch --all

Purpose:
Fetches updates from all remotes.

Example:
git fetch --all

Screenshot Proof:
(Add screenshot)

---

git pull

Syntax:
git pull

Purpose:
Fetches and merges remote changes.

Example:
git pull

Screenshot Proof:
(Add screenshot)

---

git pull --rebase

Syntax:
git pull --rebase

Purpose:
Fetches and rebases local commits.

Example:
git pull --rebase

Screenshot Proof:
(Add screenshot)

---

git push

Syntax:
git push

Purpose:
Uploads local commits to remote repository.

Example:
git push

Screenshot Proof:
(Add screenshot)

---

git push -u origin branch-name

Syntax:
git push -u origin branch-name

Purpose:
Pushes branch and sets upstream tracking.

Example:
git push -u origin main

Screenshot Proof:
(Add screenshot)

---

git push --force

Syntax:
git push --force

Purpose:
Force pushes commits to remote repository.

Example:
git push --force
