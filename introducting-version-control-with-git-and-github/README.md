# Command Line Interface (CLI) vs Graphical User Interface (GUI)
- **GUI** `Grphical User Interface`
- **CLI** `Command Line Interface`
# Understanding the Git Basics
- **Working Directory** `Current project folder`
- **Commit** `Code snapshot`
- **Branch** `Where commits are stored`
# Initializing the Repository & Creating our First Commit
- **Configuration file** `git config --global --edit`
- **Configuration display user name** `git config --global user.name`
- **Configuration set user name** `git config --global user.name "user name"`
- **Configuration set user email** `git config --global user.email "emailaddress"`
# Understanding Branches, Merging & Fixing Merge Conflicts
- **Rename a branch on which we are** `git branch -m main`
- **Checkout a new a branch and create a new branch based on a branch we are currently in** `git checkout -b feature`
- **To see commits** `git log`
- **Add and Commit our changes** `git add .` & `git commit -m 'commit message'`
- **Merge feature branch into our master/main branch: first checkout to the master/main branch** `git merge feature`
# Deleting Branches & Commits, Reverting Staged & Unstaged Changes
- **To delete a file, you have to navigate to where the file is then run the git command:** `git rm filename.extension` where `filename` is the name of the file and `extension` is the extension of the file. This will automatically add the deleted file to the staging area.
- **Revert one commit earlier and exclude the latest commit changes from the staging area and get rid of the entire commit** `git reset --hard HEAD~1` **jump back to an earlier commit** `~1` **go back one commit earlier** hard reset we update the head index and the path.
- **To delete a branch you have to checkout of the branch you want to delete** `git branch -D feature`
- **Reset your branch to the stage of the latest commit** `git checkout -- .` **undo all unstage changes** where you can `.` means every changes to discard, you could replace it with the name of the file you want to discard changes.
- **To unstage changes** `git reset filenameyouwanttounstage.extension`
# Onwards to GitHub - What & Why?
- **Store our project into a cloud** - **Cloud Storage**
- **Portfolio Page**
- **Team Projects** - **Collaboration**
- **Contribution**
# Creating a GitHub Account & a Remote Repository
- **Create a README.md in profileName/ to write a presentation about you**
- **There are two types of repository:** `local` and `remote` repository
# Understanding the Personal Access Token & "git clone"