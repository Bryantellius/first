# Git

- Use git repositories to save files
- Distributed Version Control System

- Workflow:

  - GIT PULL
  - Edit
  - Add
  - Commit: must put -m for message
  - Push

- Branches

  - Must create a branch AND checkout branch
  - Shortcut `git checkout -b <branchName>`

- Git is the tool, Github is the service for hosting remote files

Commands

- `man command` displays manual article for the command
- `cd` change directory, navigating file system
- `ls` for list
- `pwd` for print working directory
- `mkdir` creates a new directory
- `touch` create a new file
- `mv fileName location` moves the file or directory to then new location
- `mv fileName newFileName` renames file
- `echo "Some text/code"` output "Some text/code" to the console
- `echo "Some text/code" > fileName` overwrites text to file end
- `echo "Some text/code" >> fileName` appends text to file end
- `code .` for opening VSC in the current directory
- `git clone <url>` for cloning/copying remote files
- `git diff` for displaying comparison between current version and previous commit
- `git status` show git status for tracked, untracked, modified, etc files
- `git init` initializes empty git repo in directory
- `git log` displays author, date, and message for commit history
- `git add <fileName>` adds a file or files to the staging area
- `git commit -m "message"` messages and commits files in staging area
- `git checkout -b <branchName>` creates and switches to new branch
- `git branch branchName` creates new branch
- `git checkout branchName` switches to newly created branch
- `rm fileName` removes file
- `rm -r dir` removes directory recursively (add `sudo` to run command as admin for some cases)
- `git remote add origin url` adds remote repo url to local
- `git push -u origin master` first time push to Github
- `git push` pushs changes to Github
- `git push origin branchName` pushs branch to Github
- `git merge branchName` merges specified branch into current branch
- `git pull` updates local project from remote repository (fetch and merge)
- `git fetch` fetches changes from remote repo
- `git merge` merges changes from remote repo
