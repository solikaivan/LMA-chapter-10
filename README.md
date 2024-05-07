# LMA Chapter-10
 1. Fork the repo
 2. Clone the repo to your desktop
 3. Create a new branch labeled with your name
 4. Complete the exercises described in Chapter 10
  - Add a new tab to the tab bar with an associated view controller
  - Change the "View | Edit" Segmented Controller to a Switch
  - Split the Contact Field into First and Last Names
  - Add the Navigation Controller, a View Controller, and Date Picker to create the "Pick Birthdate" screen and its navigation
  - (BONUS) Write the Swift code to enable the "View | Edit" Controller
 5. Commit and Push to your repo
 6. Send me a Pull request
Administrator@dsolika MINGW64 ~
$ git clonehttps://github.com/MobileApps-Cascadia/LMA-chapter-10.git
git: 'clonehttps://github.com/MobileApps-Cascadia/LMA-chapter-10.git' is not a git command. See 'git --help'.

Administrator@dsolika MINGW64 ~
$ git clone https://github.com/MobileApps-Cascadia/LMA-chapter-10.git
Cloning into 'LMA-chapter-10'...
remote: Enumerating objects: 124, done.
remote: Total 124 (delta 0), reused 0 (delta 0), pack-reused 124
Receiving objects: 100% (124/124), 64.12 KiB | 754.00 KiB/s, done.
Resolving deltas: 100% (41/41), done.

Administrator@dsolika MINGW64 ~
$ git clone https://github.com/solikaivan/LMA-chapter-10.git
fatal: destination path 'LMA-chapter-10' already exists and is not an empty directory.

Administrator@dsolika MINGW64 ~
$ ^C

Administrator@dsolika MINGW64 ~
$ rm -rf LMA-chapter-10

Administrator@dsolika MINGW64 ~
$ git clone https://github.com/solikaivan/LMA-chapter-10.git
Cloning into 'LMA-chapter-10'...
remote: Enumerating objects: 124, done.
remote: Total 124 (delta 0), reused 0 (delta 0), pack-reused 124
Receiving objects: 100% (124/124), 64.12 KiB | 237.00 KiB/s, done.
Resolving deltas: 100% (41/41), done.

Administrator@dsolika MINGW64 ~
$ git checkout -b feature-update
fatal: not a git repository (or any of the parent directories): .git

Administrator@dsolika MINGW64 ~
$ git checkout
fatal: not a git repository (or any of the parent directories): .git

Administrator@dsolika MINGW64 ~
$ cd LMA-chapter-10

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (master)
$ git checkout -b feature-update
Switched to a new branch 'feature-update'

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (feature-update)
$ git add .

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (feature-update)
$ git commit -m "Update feature"
On branch feature-update
nothing to commit, working tree clean

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (feature-update)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (master)
$ git merge feature-update
Already up to date.

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (master)
$ git checkout -b "conflict-resolution"
Switched to a new branch 'conflict-resolution'

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (conflict-resolution)
$ git add .

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (conflict-resolution)
$ git commit -m "Resolve Conflicts"
On branch conflict-resolution
nothing to commit, working tree clean

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (conflict-resolution)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (master)
$ git push
To https://github.com/solikaivan/LMA-chapter-10.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/solikaivan/LMA-chapter-10.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (master)
$ git pull
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 1.74 KiB | 5.00 KiB/s, done.
From https://github.com/solikaivan/LMA-chapter-10
   ce01af8..1c6d487  master     -> origin/master
Updating ce01af8..1c6d487
Fast-forward
 Student Registration.html | 80 +++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 80 insertions(+)
 create mode 100644 Student Registration.html

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (master)
$ git fetch origin

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (master)
$ git merge origin/master
Already up to date.

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (master)
$ git push origin master
Everything up-to-date

Administrator@dsolika MINGW64 ~/LMA-chapter-10 (master)
$
