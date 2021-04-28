# Paathshaala

This Repo is for educational purpose

# Git basic cmd:
| Git task	    | Notes         | Git commands |
| ------------- |:-------------:| ------------:|
|Tell Git who you are      | Configure the author name and email address to be used with your commits. Note that Git strips some characters (for example trailing periods) from user.name. | git config --global user.name "Sam Smith"
git config --global user.email sam@example.com        |
|Check out a repository     | Create a working copy of a local repository:      |   git clone /path/to/repository        |
| Add files | Add one or more files to staging (index):      |  git add <filename> or git add *     |
| Commit      | Commit changes to head (but not yet to the remote repository):      |  git commit -m "Commit message"     |
|Status    | List the files you've changed and those you still need to add or commit:      |   git status    |
| Fetch      | fetch the latest history from the server and point your local master branch at it, do this:      |   git fetch     |
| Update from the remote repository with rebase    | Fetch and merge changes on the remote server to your working directory:      |   git pull --rebase        |
| Push    | Send changes to the master branch of your remote repository:      |   git push origin <branch> |
