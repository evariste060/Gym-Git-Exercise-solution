# Git exercise
## Bundle 1
### Exercise 1
```Bash
   10  mkdir myproject
   11  cd myproject
   12  echo hello> index.html
   13  ls
   14  git status
   15  git init
   16  git status
   17  git add index.html
   18  git status
   19  git branch
   20  git branch modified-index.html
   21  git branch modified-index-html
   22  git branch modified
   23  cd ../
   24  git branch modified
   25  cd myproject
   26  git status
   27  git branch
   28  code
   29  code .
   30  git branch modified
   31  git branch -m main master
   32  git branch
   33  git branch modified
   34  echo >README.md
   35  ls
   36  code .
   37  git add --all
   38  git status
   39  git commit -m 'checking for how it works'
   40  git branch
   41  git branch modified-readme-file
   42  git branch
   43  git checkout modified-readme-file
   44  git status
   45  encho >style.css
   46  echo >style.css
   47  ls
   48  git checkout -b emergency-fix
   49  ls
   50  git status
   51  git branch -d emergency-fix
   52  git commit -m 'added new file of style'
   53  git add style.css
   54  git commit -m 'added new file of style'
   55  git status
   56  git branch checkout master
   57  git status
   58  git checkout master
   59  git status
   60  ls
   61  git branch -d emergency-fix
   62  cd ../
   63  clear
   64  mkdir git-exercises
   65  cd git-exercises
   66  echo >inde.html
   67  git mv ende.html index.html
   68  clear
   69  mkdir git-exercises
   70  cd git-exercises
   71  echo >index.html
   72  echo >README.md
   73  code .
   74  git init
   75  git branch -m master
   76  git branch -m main
   77  git add --all
   78  git commit -m 'First commit'
   80  git push -u origin main
   90  git remote set-url origin https://github.com/evariste060/Gym-Git-Exercise-Solutions.git
   91  git push origin main
   92  git branch dev
   93  git checkout dev
   94  git branch test
   95  git branch
   96  git branch -d test
   97  git branch -d dev
   98  git checkout main
   99  git branch -d dev
  100  git branch
  101  git branch dev
  102  git push origin dev
  103  git checkout dev
  104  git branch test
  105  git push origin test
  106  git branch -d test
  107  git push origin --delete test
  108  git status
  109  git  checkout main
  110  git status
  111  git add README.md
  112  git status
  113  cd ../
  114  git status
  115  cd ../
  116  cd git-exercise
  117  cd myproject
  118  git status
  119  ls
  120  git add README.md
  121  git commit -m 'updated README File'
  122  git push origin main
  123  git push origin master
  124  git remote
  125  git remote add https://github.com/evariste060/Gym-Git-Exercise-Solutions.git
  126  git status
  127  git branch -m master main
  128  git status
  129  git push origin main
  130  git push -u origin main
  131  clear
  132  echo >index.html
  133  echo >README.md
  134  git init
  135  git branch -m master
  136  git branch main
  137  git branch -m main
  138  git branch -m main master
  139  clear
  140  cd ../
  141  mkdir git-exercise
  142  git init
  143  echo >index.html
  144  echo >README.md
  145  cd .
  146  code .
  147  cd git-exercise
  148  code .
  149  echo >index.html
  150  echo >README.md
  151  git init
  152  git branch -m main master
  153  git branch -m master main
  154  git add --all
  155  git status
  156  git commit -m ' initial commit'
  157  git remote add origin https://github.com/evariste060/Gym-Git-Exercise-solution.git
  158  git push -u origin main
  159  git branch dev
  160  git branch list
  161  git branch
  162  git branch -d list
  163  git branch push dev
  164  git push origin dev
  165  git checkout dev
  166  git branch test
  167  git push origin test
  168  git branch -d test
  169  git push --delete test
  170  git push origin --delete test
  171  git status
  172  git checkout main
  173  git status
  174  git add README.md
  175  git commit -m 'update README File '
  176  git push -u origin main

```
### Exercise 2
```bash
  179  git add home.html
  180  git status
  181  git stash
  182  echo >about.html
  183  git add about.html
  184  git stash
182  echo >about.html
  183  git add about.html
  184  git stash
  185  echo>team.html
  186  git add team.html
  187  git stash
  188  git stash list
  189  git stash pop stash@{1}
  190  git stash pop stash@{1}
  191  git commit -m 'new created file'
  192  git push -u origin main
  193  git stash pop
  194  git reset --hard
```
## Bundle 2
### Exercise 1
```bash

user@LAPTOP-300LKL1I MINGW64 ~ (main)
$ cd git-exercise

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/bundle-2)
$ git branch
  dev
* ft/bundle-2
  main

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/bundle-2)
$ ls
README.md  about.html  home.html  index.html  services.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/bundle-2)
$ git status
On branch ft/bundle-2
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   services.html

no changes added to commit (use "git add" and/or "git commit -a")

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/bundle-2)
$ git add services.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/bundle-2)
$ git status
On branch ft/bundle-2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   services.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md


user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/bundle-2)
$ git stash
Saved working directory and index state WIP on ft/bundle-2: 9465fc5 added services pages

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/bundle-2)
$ git stash pop
On branch ft/bundle-2
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   services.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped refs/stash@{0} (c3a401f3eaf7f06009421ba6b2cd7c2b49e7b280)

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/bundle-2)
$ git add services.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/bundle-2)
$ git status
On branch ft/bundle-2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   services.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md


user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/bundle-2)
$ git commit -m 'added pages of services'
[ft/bundle-2 91ece85] added pages of services
 1 file changed, 1 insertion(+), 1 deletion(-)

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/bundle-2)
$ git push -u origin ft/bundle-2
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 702 bytes | 702.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/evariste060/Gym-Git-Exercise-solution/pull/new/ft/bundle-2
remote:
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/bundle-2)
$ git checkout main
M       README.md
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git merge --no-ff ft/bundle-2
Merge made by the 'ort' strategy.
 services.html | 11 +++++++++++
 1 file changed, 11 insertions(+)
 create mode 100644 services.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ ls
README.md  about.html  home.html  index.html  services.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git push -u origin main
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 265 bytes | 265.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
   947eba5..329120f  main -> main
branch 'main' set up to track 'origin/main'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$
```









