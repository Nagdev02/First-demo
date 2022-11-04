#demo

kiranpangeni@Kirans-MacBook-Pro GIT % cd First-demo 
kiranpangeni@Kirans-MacBook-Pro First-demo % la
zsh: command not found: la
kiranpangeni@Kirans-MacBook-Pro First-demo % ls -la
total 8
drwxr-xr-x@  4 kiranpangeni  staff  128 Nov  3 21:01 .
drwxr-xr-x@  3 kiranpangeni  staff   96 Nov  3 21:00 ..
drwxr-xr-x@ 12 kiranpangeni  staff  384 Nov  3 21:01 .git
-rw-r--r--@  1 kiranpangeni  staff   26 Nov  3 21:00 README.md
kiranpangeni@Kirans-MacBook-Pro First-demo % git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)
kiranpangeni@Kirans-MacBook-Pro First-demo % git add .
kiranpangeni@Kirans-MacBook-Pro First-demo % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

kiranpangeni@Kirans-MacBook-Pro First-demo % git commit -
m "Added index.html"
[main 6c9dab1] Added index.html
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html
kiranpangeni@Kirans-MacBook-Pro First-demo % git push
kiranpangeni@Kirans-MacBook-Pro First-demo % cd
kiranpangeni@Kirans-MacBook-Pro ~ % cd Desktop
kiranpangeni@Kirans-MacBook-Pro Desktop % cd GIT 
kiranpangeni@Kirans-MacBook-Pro GIT % cd demo\ 2 
kiranpangeni@Kirans-MacBook-Pro demo 2 % ls
kiranpangeni@Kirans-MacBook-Pro demo 2 % ls -la
total 0
drwxr-xr-x@ 2 kiranpangeni  staff   64 Nov  3 21:19 .
drwxr-xr-x@ 4 kiranpangeni  staff  128 Nov  3 21:19 ..
kiranpangeni@Kirans-MacBook-Pro demo 2 % git init
Initialized empty Git repository in /Users/kiranpangeni/Desktop/GIT/demo 2/.git/
kiranpangeni@Kirans-MacBook-Pro demo 2 % git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
kiranpangeni@Kirans-MacBook-Pro demo 2 % git add READ
ME.md
kiranpangeni@Kirans-MacBook-Pro demo 2 % git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

kiranpangeni@Kirans-MacBook-Pro demo 2 % git commit -
m "Created README" -m "description"
[main (root-commit) 888a012] Created README
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
kiranpangeni@Kirans-MacBook-Pro demo 2 % git push ori
gin master
error: src refspec master does not match any
error: failed to push some refs to 'origin'
kiranpangeni@Kirans-MacBook-Pro demo 2 % git push 
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>

kiranpangeni@Kirans-MacBook-Pro demo 2 % git remote a
dd origin git@github.com:Nagdev02/demo-2.git
kiranpangeni@Kirans-MacBook-Pro demo 2 % git remote -
v
origin  git@github.com:Nagdev02/demo-2.git (fetch)
origin  git@github.com:Nagdev02/demo-2.git (push)
kiranpangeni@Kirans-MacBook-Pro demo 2 % git push ori
gin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:Nagdev02/demo-2.git'
kiranpangeni@Kirans-MacBook-Pro demo 2 % git pusg
git: 'pusg' is not a git command. See 'git --help'.

The most similar command is
        push
kiranpangeni@Kirans-MacBook-Pro demo 2 % git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

kiranpangeni@Kirans-MacBook-Pro demo 2 %     git push --set-upstream origin main
Enter passphrase for key '/Users/kiranpangeni/.ssh/id_ed25519': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 227 bytes | 227.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Nagdev02/demo-2.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
kiranpangeni@Kirans-MacBook-Pro demo 2 % 
