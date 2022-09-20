# Important git commands:

`git init`: Turns a directory into a git repository

`git clone`: Copy a repository from the internet (e.g. GitHub)

`git status`: Shows current information about repository, like the current branch and modified or staged files

`git log`: Lists version history for the current branchqqq

`git add . ` Stages all changes in the directory for commiting.

`git add [filename]`: Stages only this file

`git commit -m "message"`: Commit staged files with inline commit message

`git push`: Push current history to a remote like GitHub

`git pull`: Pull history of remote to local machine, might result in merge conflicts

`git checkout -b "new_branch_name"`: Create a new branch from the current state and switch to it

`git checkout [commit hash or branch name or HEAD^ or HEAD~x]`: Move HEAD to specified commit, either explicitely through a commit hash, a branch name or relatively through an interger offset from the current HEAD.

`git merge [branch]`: Merge specified branch into HEAD, might need to resolve conflicts

`git rebase [branch]` Reapplies the commits of the current branch on top of the specified branch, as if you had worked on it from the beginning. Leads to a nicer, linear commit history.

`git restore . `: Delete unstaged changes and return to latest commit

`git reset --hard [commit]`: Move HEAD to specified commit, deleting unsaved changes in the process.
