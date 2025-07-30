# Git exercise
## Bundle 1
### Exercise 1
```Bash
user@LAPTOP-300LKL1I MINGW64 ~ (main)
$ cd git-exercise

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ code .

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ echo >index.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ echo >README.md

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git init
Initialized empty Git repository in C:/Users/user/git-exercise/.git/

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git branch -m main master

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (master)
$ git branch -m master main

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git add --all
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   index.html


user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git commit -m ' initial commit'
[main (root-commit) 2750fa4]  initial commit
 2 files changed, 12 insertions(+)
 create mode 100644 README.md
 create mode 100644 index.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git remote add origin https://github.com/evariste060/Gym-Git-Exercise-solution.git

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 418 bytes | 418.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git branch dev
ser@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/evariste060/Gym-Git-Exercise-solution/pull/new/dev
remote:
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
 * [new branch]      dev -> dev
 user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (dev)
$ git branch test
user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (dev)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/evariste060/Gym-Git-Exercise-solution/pull/new/test
remote:
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
 * [new branch]      test -> test
user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (dev)
$ git branch -d test
Deleted branch test (was 2750fa4).
user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (dev)
$ git push origin --delete test
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
 - [deleted] 








