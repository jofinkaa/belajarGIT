Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
…

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ git branch
* Tugas-git
  main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ echo "Ini adalah template untuk tugas  GIT" >  Tugas-Git.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Git.txt

nothing added to commit but untracked files present (use "git add" to track)

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt
warning: in the working copy of 'Tugas-Git.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Git.txt


LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan dan mengubah Tugas-Git.txt"
[Tugas-git 53411f7] Menambahkan dan mengubah Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-git
Updating 4e30b9e..53411f7
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ ls
README.md  Tugas-Git.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 341 bytes | 341.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/jofinkaa/belajarGIT.git
   4e30b9e..53411f7  main -> main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$  git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ git branch
  Tugas-git
* Tugas-html
  main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ echo "ini adalah template untuk tugas GIT" > Tugas-html.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-html.txt

nothing added to commit but untracked files present (use "git add" to track)

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
warning: in the working copy of 'Tugas-html.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-html.txt


LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ git commit -m "menambah dan mengubah Tugas-html.txt"
[Tugas-html 82a6114] menambah dan mengubah Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas.html
merge: Tugas.html - not something we can merge

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-html
Updating 53411f7..82a6114
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ 1s
bash: 1s: command not found

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ ls
README.md  Tugas-Git.txt  Tugas-html.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 364 bytes | 364.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/jofinkaa/belajarGIT.git
   53411f7..82a6114  main -> main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ git branch
* Tugas-css
  Tugas-git
  Tugas-html
  main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ echo "ini adalah template untuk tugas GIT" > Tugas-css.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-css.txt

nothing added to commit but untracked files present (use "git add" to track)

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
warning: in the working copy of 'Tugas-css.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-css.txt


LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ git commit -m "menambah dan mengubah Tugas-css.txt"
[Tugas-css d51e967] menambah dan mengubah Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
nothing to commit, working tree clean

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-css
Updating 82a6114..d51e967
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ ls
README.md  Tugas-Git.txt  Tugas-css.txt  Tugas-html.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 246 bytes | 246.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/jofinkaa/belajarGIT.git
   82a6114..d51e967  main -> main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* Tugas-js
  main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ echo "ini adalah template untuk tugas GIT" > Tugas-js.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-js.txt

nothing added to commit but untracked files present (use "git add" to track)

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ git add Tugas-js.txt
warning: in the working copy of 'Tugas-js.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-js.txt


LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ git commit -m "menambah dan mengubah Tugas-js.txt"
[Tugas-js 863537d] menambah dan mengubah Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-js
Updating d51e967..863537d
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ ls
README.md  Tugas-Git.txt  Tugas-css.txt  Tugas-html.txt  Tugas-js.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 244 bytes | 244.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/jofinkaa/belajarGIT.git
   d51e967..863537d  main -> main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* Tugas-midProject
  main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ echo "ini adalah template untuk tugas GIT" > Tugas-midProject.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-midProject
        Tugas-midProject.txt

nothing added to commit but untracked files present (use "git add" to track)

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt
warning: in the working copy of 'Tugas-midProject.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-midProject


LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git add .

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject
        new file:   Tugas-midProject.txt


LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git commit -m "Menambah dan mengubah Tugas-midProject.txt"
[Tugas-midProject 1b63368] Menambah dan mengubah Tugas-midProject.txt
 2 files changed, 1 insertion(+)
 create mode 100644 Tugas-midProject
 create mode 100644 Tugas-midProject.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    Tugas-midProject

no changes added to commit (use "git add" and/or "git commit -a")

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git add .

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git commit -m "menambah dan mengubah Tugas-midProject.txt"
[Tugas-midProject 09a778f] menambah dan mengubah Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 Tugas-midProject

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
nothing to commit, working tree clean

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-midProject
Updating 863537d..09a778f
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ ls
README.md  Tugas-Git.txt  Tugas-css.txt  Tugas-html.txt  Tugas-js.txt  Tugas-midProject.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 514 bytes | 514.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/jofinkaa/belajarGIT.git
   863537d..09a778f  main -> main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* Tugas-php
  main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ echo "ini adalah template untuk tugas GIT" > Tugas-php.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-php.txt

nothing added to commit but untracked files present (use "git add" to track)

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ git add Tugas-php.txt
warning: in the working copy of 'Tugas-php.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-php.txt


LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ git commit -m "menambah dan mengubah Tugas-php.txt"
[Tugas-php 6262ffd] menambah dan mengubah Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
nothing to commit, working tree clean

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-php
Updating 09a778f..6262ffd
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ ls
README.md  Tugas-Git.txt  Tugas-css.txt  Tugas-html.txt  Tugas-js.txt  Tugas-midProject.txt  Tugas-php.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 250 bytes | 250.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/jofinkaa/belajarGIT.git
   09a778f..6262ffd  main -> main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ git branch
  Tugas-css
* Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
  main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ echo "ini adalah template untuk tugas GIT" > Tugas-finalProject.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-finalProject.txt

nothing added to commit but untracked files present (use "git add" to track)

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt
warning: in the working copy of 'Tugas-finalProject.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-finalProject.txt


LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ git commit -m "menambah dan mengubah Tugas-finalProject.txt"
[Tugas-finalProject 377b718] menambah dan mengubah Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
nothing to commit, working tree clean

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 6262ffd..377b718
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ ls
README.md  Tugas-Git.txt  Tugas-css.txt  Tugas-finalProject.txt  Tugas-html.txt  Tugas-js.txt  Tugas-midProject.txt  Tugas-php.txt

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 266 bytes | 266.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/jofinkaa/belajarGIT.git
   6262ffd..377b718  main -> main

LENOVO@LAPTOP-3C68774V MINGW64 /d/TugasWeb/belajarGIT (main)
$
