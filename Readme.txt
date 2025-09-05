User@DESKTOP-9A9V2MJ MINGW64 ~
$ cd desktop

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop
$ mkdir Ytac_IT120_Act1

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop
$ cd Ytac_IT120_Act1

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1
$ git init
Initialized empty Git repository in C:/Users/User/Desktop/Ytac_IT120_Act1/.git/

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ touch Profile.txt Education.txt Background.txt Readme.txt Test.py

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git add .

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Background.txt
        new file:   Education.txt
        new file:   Profile.txt
        new file:   Readme.txt
        new file:   Test.py

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git commit -m "Initial commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'User@DESKTOP-9A9V2MJ.(none)')

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git config --global user.name "jena1234586"

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git config --global user.email "jenalynperezytac@gmail.com"

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git commit -m "Initial commit"
[master (root-commit) f40ea66] Initial commit
 5 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git remote add origin https://github.com/jena1234586/YTAC_IT120_ACT1.git

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git remote -v
origin  https://github.com/jena1234586/YTAC_IT120_ACT1.git (fetch)
origin  https://github.com/jena1234586/YTAC_IT120_ACT1.git (push)

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git branch -M master

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git push -u origin master
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (7/7), 885 bytes | 295.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/jena1234586/YTAC_IT120_ACT1.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git checkout -b Ytac_B1
Switched to a new branch 'Ytac_B1'

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B1)
$ git branch
* Ytac_B1
  master

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B1)
$ git add Profile.txt

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B1)
$ git commit -m "Added Data"
[Ytac_B1 f74b819] Added Data
 1 file changed, 8 insertions(+), 1 deletion(-)

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B1)
$ git push origin Ytac_B1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 472 bytes | 472.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Ytac_B1' on GitHub by visiting:
remote:      https://github.com/jena1234586/YTAC_IT120_ACT1/pull/new/Ytac_B1
remote:
To https://github.com/jena1234586/YTAC_IT120_ACT1.git
 * [new branch]      Ytac_B1 -> Ytac_B1

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B1)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git checkout -b Ytac_B2
Switched to a new branch 'Ytac_B2'

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B2)
$ git branch
  Ytac_B1
* Ytac_B2
  master

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B2)
$ git add Education.txt

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B2)
$ git commit -m "Added Data"
[Ytac_B2 09d6aad] Added Data
 1 file changed, 5 insertions(+), 1 deletion(-)

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B2)
$ git push origin Ytac_B2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 441 bytes | 441.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Ytac_B2' on GitHub by visiting:
remote:      https://github.com/jena1234586/YTAC_IT120_ACT1/pull/new/Ytac_B2
remote:
To https://github.com/jena1234586/YTAC_IT120_ACT1.git
 * [new branch]      Ytac_B2 -> Ytac_B2

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B2)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git checkout -b Ytac_B3
Switched to a new branch 'Ytac_B3'

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B3)
$ git branch
  Ytac_B1
  Ytac_B2
* Ytac_B3
  master

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B3)
$ git add Background.txt

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B3)
$ git rm Test.py
rm 'Test.py'

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B3)
$ git commit -m "Added Data and removed Test.py"
[Ytac_B3 1372cb8] Added Data and removed Test.py
 2 files changed, 4 insertions(+), 4 deletions(-)
 delete mode 100644 Test.py

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B3)
$ git push origin Ytac_B3
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 373 bytes | 373.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Ytac_B3' on GitHub by visiting:
remote:      https://github.com/jena1234586/YTAC_IT120_ACT1/pull/new/Ytac_B3
remote:
To https://github.com/jena1234586/YTAC_IT120_ACT1.git
 * [new branch]      Ytac_B3 -> Ytac_B3

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B3)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (master)
$ git checkout -b Ytac_B4
Switched to a new branch 'Ytac_B4'

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B4)
$ git branch
  Ytac_B1
  Ytac_B2
  Ytac_B3
* Ytac_B4
  master

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B4)
$ git add Readme.txt

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B4)
$ git rm Test.py
rm 'Test.py'

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B4)
$ git commit -m "Updated Git Command and removed Test.py"
[Ytac_B4 8f65b39] Updated Git Command and removed Test.py
 2 files changed, 208 insertions(+), 4 deletions(-)
 delete mode 100644 Test.py

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B4)
$ git push origin Ytac_B4
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.62 KiB | 1.62 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Ytac_B4' on GitHub by visiting:
remote:      https://github.com/jena1234586/YTAC_IT120_ACT1/pull/new/Ytac_B4
remote:
To https://github.com/jena1234586/YTAC_IT120_ACT1.git
 * [new branch]      Ytac_B4 -> Ytac_B4

User@DESKTOP-9A9V2MJ MINGW64 ~/desktop/Ytac_IT120_Act1 (Ytac_B4)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
