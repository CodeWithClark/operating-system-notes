- **Basic Snapshotting**

  - **git init:** Initialize a new Git repository in the current directory.
  - **git clone <repository_url>** Clone a remote repository to your local machine.
  - **git add <file>** Add a file or changes to the staging area.
  - **git commit -m "<message>"** Commit staged changes with a descriptive message.
  - **git status** Show the status of files (modified, staged, untracked).
  - **git diff** Show changes between commits, or the working tree and the staging area.

  **Branching & Merging**

  - **git branch** List all existing branches.
  - **git branch <branch_name>** Create a new branch.
  - **git checkout <branch_name>** Switch to a different branch.
  - **git merge <branch_name>** Merge a specified branch into the current branch.

  **Inspecting History**

  - **git log** Show the commit history of the current branch.
  - **git show <commit_hash>** Show details of a specific commit.
  - **git blame <file>** Show who last modified each line of a file and when.

  **Undoing Changes**

  - **git reset <file>** Unstage a file from the staging area.
  - **git reset --hard** Discard local changes and revert to the last commit.
  - **git revert <commit_hash>** Create a new commit that reverts the changes of a previous commit.

  **Remote Repositories**

  - **git remote add origin <repository_url>** Add a remote repository named "origin".
  - **git push origin <branch_name>** Push changes from local branch origina to the remote repository.
    - **git push origin main**
  - **git pull origin <branch_name>** Fetch and merge changes from the remote repository.

  **Advanced Commands**

  - **git rebase <branch_name>** Rebase the current branch onto another branch.
  - **git cherry-pick <commit_hash>** Pick a commit from another branch and apply it to the current branch.
  - **git stash** Temporarily save uncommitted changes.
  - **git tag <tag_name>** Create a tag to mark a specific point in history.