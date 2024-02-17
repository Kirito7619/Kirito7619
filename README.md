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
$ git remote add origin https://github.com/14Mahammad/trial.git

Deevesh Pingle@DESKTOP-4G88TE5 MINGW64 ~/OneDrive/Desktop/casetools (master)
$ git push -u origin 
