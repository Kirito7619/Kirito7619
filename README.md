Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop
$ mkdir casetools

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop
$ cd casetools

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools
$ touch vikas.txt

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools
$ echo "mmm" >vikas.txt

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools
$ git init
Initialized empty Git repository in C:/Users/Deevesh Pingle/OneDrive/Desktop/casetools/.git/

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git add *
warning: in the working copy of 'vikas.txt', LF will be replaced by CRLF the next time Git touches it

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git commit -m 'first commit'
[master (root-commit) 2cd434e] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 vikas.txt

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git log
commit 2cd434eb95e12fc87b5a54ae8cd9d792c4302d18 (HEAD -> master)
Author: Deevesh Pingle <deeveshpingle7875@gmail.com>
Date:   Sat Feb 17 09:02:43 2024 +0530

    first commit

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git status
On branch master
nothing to commit, working tree clean

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ echo "vikas" >>vikas.txt

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git commit -m
error: switch `m' requires a value

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git commit -m "second commit"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   vikas.txt

no changes added to commit (use "git add" and/or "git commit -a")

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git add *
warning: in the working copy of 'vikas.txt', LF will be replaced by CRLF the next time Git touches it

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git commit -m "second commit"
[master bb1b90c] second commit
 1 file changed, 1 insertion(+)

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git remote add origin https://github.com/14Mahammad/trial.git

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git push -u origin master
remote: Permission to 14Mahammad/trial.git denied to deeveshpingle.
fatal: unable to access 'https://github.com/14Mahammad/trial.git/': The requested URL returned error: 403

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git remote add origin https://github.com/14Mahammad/trial.git
error: remote origin already exists.

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/14Mahammad/trial.git'

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git push -u origin master
remote: Permission to 14Mahammad/trial.git denied to deeveshpingle.
fatal: unable to access 'https://github.com/14Mahammad/trial.git/': The requested URL returned error: 403

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git log
commit bb1b90cfa953260562d7b15a112eb7fa7c255565 (HEAD -> master)
Author: Deevesh Pingle <deeveshpingle7875@gmail.com>
Date:   Sat Feb 17 09:06:45 2024 +0530

    second commit

commit 2cd434eb95e12fc87b5a54ae8cd9d792c4302d18
Author: Deevesh Pingle <deeveshpingle7875@gmail.com>
Date:   Sat Feb 17 09:02:43 2024 +0530

    first commit

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git config --global user.name "mahammad"

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git config --global user.email "mahammad@mmm.com"

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git log
commit bb1b90cfa953260562d7b15a112eb7fa7c255565 (HEAD -> master)
Author: Deevesh Pingle <deeveshpingle7875@gmail.com>
Date:   Sat Feb 17 09:06:45 2024 +0530

    second commit

commit 2cd434eb95e12fc87b5a54ae8cd9d792c4302d18
Author: Deevesh Pingle <deeveshpingle7875@gmail.com>
Date:   Sat Feb 17 09:02:43 2024 +0530

    first commit

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git commit -m "third commit"
On branch master
nothing to commit, working tree clean

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git push -u origin master
remote: Permission to 14Mahammad/trial.git denied to deeveshpingle.
fatal: unable to access 'https://github.com/14Mahammad/trial.git/': The requested URL returned error: 403
