Answer 1: git version 2.30.0.windows.2

Answer 2:  git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Mason Slaughter
user.email=ms169719@ohio.edu
PS C:\Users\healt\Documents\cs2400\git-lab>

Answer 3: When you enter the git add --help command it brings you a git-add manual page with different commands, a description, etc.    

Answer 4:  git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md
Answer 5:  git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md
Answer 6:  git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md
Answer 7:  git status
On branch master
nothing to commit, working tree clean

Answer 8: git log
commit 9767f8316af0ec7ac61e59b8ed18964d4b04fb25 (HEAD -> master)
Author: Mason Slaughter <ms169719@ohio.edu>
Date:   Wed Jan 27 16:44:14 2021 -0500

    Initial commit

Answer 9:  git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Answer 10: cat  README.md
ms169719@ohio.edu
Recorded in notepad.
  yes 


Answer 11:  git push
To https://github.com/ms169719/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/ms169719/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.

Answer 11:  git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 726 bytes | 90.00 KiB/s, done.
From https://github.com/ms169719/git-lab
   40e3604..d7c4267  main       -> origin/main
Updating 40e3604..d7c4267
Fast-forward
 README.md | Bin 84 -> 66 bytes
 1 file changed, 0 insertions(+), 0 deletions(-)

Answer 12: cat  README.md
ms169719@ohio.edu
Recorded in notepad.
CS 2400, section 107  yes

Answer 13:   Directory: C:\Users\healt\documents\cs2400


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----        1/27/2021   5:24 PM                git-lab
d-----        1/27/2021   5:32 PM                git-lab-2
d-----        1/20/2021   5:48 PM                hw
d-----        1/20/2021   6:05 PM                labs



  