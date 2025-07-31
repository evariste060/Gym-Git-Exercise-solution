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
## Bundle 2
### Exercise 2
```bash

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git pull
Already up to date.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git branch ft/service-redesign

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git branch
  dev
  ft/bundle-2
  ft/service-redesign
* main

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git  checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/service-redesign)
$ git status
On branch ft/service-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   services.html

no changes added to commit (use "git add" and/or "git commit -a")

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/service-redesign)
$ git add services.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/service-redesign)
$ git commit -m 'designed pages of services
> git commit -m 'designed pages of services'
> git status
> q
>
.git/          about.html     index.html
README.md      home.html      services.html
> :
> :wq
> ^C

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/service-redesign)
$ git commit -m 'designed pages of services '
[ft/service-redesign 4ef73be] designed pages of services
 1 file changed, 2 insertions(+), 1 deletion(-)

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/service-redesign)
$ git push -u origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 349 bytes | 349.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/evariste060/Gym-Git-Exercise-solution/pull/new/ft/service-redesign
remote:
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   services.html

no changes added to commit (use "git add" and/or "git commit -a")

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git add services.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git commit -m 'this may be good appearance of the services pages'
[main 9d4aa1e] this may be good appearance of the services pages
 1 file changed, 1 insertion(+), 1 deletion(-)

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 368 bytes | 368.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
   d9b7ee4..9d4aa1e  main -> main
branch 'main' set up to track 'origin/main'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/service-redesign)
$ git diff main ft/service-redesign
diff --git a/services.html b/services.html
index ba9f577..cc4b503 100644
--- a/services.html
+++ b/services.html
@@ -3,9 +3,10 @@
 <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
-    <title>Services </title>
+    <title>Services vail </title>
 </head>
 <body>
-    This may be good to you just test it
+    updated varsion of services pages
+    Here is services we offer
 </body>
 </html>
\ No newline at end of file

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/service-redesign)
$ git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/service-redesign|MERGING)
$ git status
On branch ft/service-redesign
Your branch is up to date with 'origin/ft/service-redesign'.

You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both modified:   services.html

no changes added to commit (use "git add" and/or "git commit -a")

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/service-redesign|MERGING)
$ git add services.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/service-redesign|MERGING)
$ git commit
[ft/service-redesign acbc7c7] Merge branch 'main' into ft/service-redesign

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/service-redesign)
$ git push -u origin ft/service-redesign
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 414 bytes | 414.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
   4ef73be..acbc7c7  ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.
```
# Bundle 3
## Exercise 1
```bash

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/team-page)
$ git add team.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/team-page)
$ git status
On branch ft/team-page
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html


user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/team-page)
$ git commit -m 'added page of team'
[ft/team-page b84f49b] added page of team
 1 file changed, 11 insertions(+)
 create mode 100644 team.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/team-page)
$ git push -u ft/team-page
fatal: 'ft/team-page' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/team-page)
$ git push -u origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 448 bytes | 448.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/evariste060/Gym-Git-Exercise-solution/pull/new/ft/team-page
remote:
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/team-page)
$ ^C

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git branch ft/contact-page

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/team-page)
$ git log
commit b84f49bf355208806cb8df9b20c9ea6534e1eec7 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Evariste Nkurunziza <nkurunzizaevariste060@gmail.com>
Date:   Thu Jul 31 13:02:01 2025 +1100

    added page of team

commit 7a8b2dda12cf5c362de1d4f7f46defb469ce874e (origin/main, origin/HEAD, main, ft/contact-page)
Author: Evariste Nkurunziza <nkurunzizaevariste060@gmail.com>
Date:   Thu Jul 31 12:49:00 2025 +1100

    Updated README  file including bundle 2 Exercise 2

commit 9d4aa1e231c50c8274a67b68f24f031db3c86b2b
Author: Evariste Nkurunziza <nkurunzizaevariste060@gmail.com>
Date:   Thu Jul 31 12:05:59 2025 +1100

    this may be good appearance of the services pages

commit d9b7ee450f74c71748765c29dffd50bc8e9ec1b1
Author: Evariste Nkurunziza <nkurunzizaevariste060@gmail.com>
Date:   Thu Jul 31 11:27:44 2025 +1100

    updated README file with bundle2 exercise 1

commit 329120f2782e4f1aac49202d062c956f9e07fccc
Merge: 947eba5 91ece85
Author: Evariste Nkurunziza <nkurunzizaevariste060@gmail.com>
Date:   Thu Jul 31 11:16:01 2025 +1100

    Merge branch 'ft/bundle-2'
    Added new HTML pages of services

commit 91ece85868983e064144d0d26139845efa8e8877 (origin/ft/bundle-2, ft/bundle-2)
Author: Evariste Nkurunziza <nkurunzizaevariste060@gmail.com>
Date:   Thu Jul 31 10:11:13 2025 +1100

    added pages of services

commit 9465fc592c9a1154e865f461c4ec391a202e75dd
Author: Evariste Nkurunziza <nkurunzizaevariste060@gmail.com>
Date:   Wed Jul 30 21:54:35 2025 +1100

    added services pages


user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/contact-page)
$ git cherry-pick b84f49bf355208806cb8df9b20c9ea6534e1eec7
[ft/contact-page 0b5f5c2] added page of team
 Date: Thu Jul 31 13:02:01 2025 +1100
 1 file changed, 11 insertions(+)
 create mode 100644 team.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/contact-page)
$ git status
On branch ft/contact-page
nothing to commit, working tree clean

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/contact-page)
$ ls
README.md  about.html  home.html  index.html  services.html  team.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/contact-page)
$ git status
On branch ft/contact-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        contact.html

nothing added to commit but untracked files present (use "git add" to track)

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/contact-page)
$ git add contact.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/contact-page)
$ git commit -m 'added page of contact'
[ft/contact-page 4d5af9d] added page of contact
 1 file changed, 11 insertions(+)
 create mode 100644 contact.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/contact-page)
$ git push -u origin ft/contact-page
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 737 bytes | 368.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/evariste060/Gym-Git-Exercise-solution/pull/new/ft/contact-page
remote:
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/contact-page)
$ git branch ft/faq-page

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/contact-page)
$ git checkout ft/faq-page
Switched to branch 'ft/faq-page'

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/faq-page)
$ git add faq.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/faq-page)
$ git commit -m 'added faq page'
[ft/faq-page 4c39fb5] added faq page
 1 file changed, 11 insertions(+)
 create mode 100644 faq.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/faq-page)
$ git push -u origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 438 bytes | 438.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/evariste060/Gym-Git-Exercise-solution/pull/new/ft/faq-page
remote:
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/faq-page)
$ git revert b84f49bf355208806cb8df9b20c9ea6534e1eec7
[ft/faq-page 315b962] Revert "added page of team"
 1 file changed, 11 deletions(-)
 delete mode 100644 team.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/faq-page)
$ git push -u origin ft/faq-page
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 287 bytes | 287.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
   4c39fb5..315b962  ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

```
# Exercise 2
```bash

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git checkout ft/faq-page
Switched to branch 'ft/faq-page'
Your branch is up to date with 'origin/ft/faq-page'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/faq-page)
$ git branch ft/home-page-redesign

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/faq-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git add home.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git commit -m 'update home page'
[main b3727d4] update home page
 1 file changed, 3 insertions(+), 1 deletion(-)

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 361 bytes | 361.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
   2c1fba0..b3727d4  main -> main
branch 'main' set up to track 'origin/main'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/home-page-redesign)
$ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/home-page-redesign)
$ git status
On branch ft/home-page-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/home-page-redesign)
$ git  add home.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/home-page-redesign)
$ git commit -m 'update home pages'
[ft/home-page-redesign cbe28a9] update home pages
 1 file changed, 1 insertion(+)

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/home-page-redesign)
$ git push -u origin ft/home-page-redesign
Enumerating objects: 16, done.
Counting objects: 100% (16/16), done.
Delta compression using up to 16 threads
Compressing objects: 100% (14/14), done.
Writing objects: 100% (14/14), 1.50 KiB | 1.50 MiB/s, done.
Total 14 (delta 8), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (8/8), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/evariste060/Gym-Git-Exercise-solution/pull/new/ft/home-page-redesign
remote:
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.
```
# Bundle 4
## Exercise 1
```bash

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git remote add git-copy https://github.com/evariste060/Gym-Git-Exercise-solution2.git

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git add home.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git commit -m 'Update home page of our projects'
[main 34f14fc] Update home page of our projects
 1 file changed, 1 insertion(+)

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 367 bytes | 367.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
   8abffc9..34f14fc  main -> main
branch 'main' set up to track 'origin/main'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git push -u git-copy main
Enumerating objects: 47, done.
Counting objects: 100% (47/47), done.
Delta compression using up to 16 threads
Compressing objects: 100% (46/46), done.
Writing objects: 100% (47/47), 9.44 KiB | 568.00 KiB/s, done.
Total 47 (delta 24), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (24/24), done.
To https://github.com/evariste060/Gym-Git-Exercise-solution2.git
 * [new branch]      main -> main
branch 'main' set up to track 'git-copy/main'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$
user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git remote add git-copy https://github.com/evariste060/Gym-Git-Exercise-solution2.git

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git add home.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git commit -m 'Update home page of our projects'
[main 34f14fc] Update home page of our projects
 1 file changed, 1 insertion(+)

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 367 bytes | 367.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
   8abffc9..34f14fc  main -> main
branch 'main' set up to track 'origin/main'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git push -u git-copy main
Enumerating objects: 47, done.
Counting objects: 100% (47/47), done.
Delta compression using up to 16 threads
Compressing objects: 100% (46/46), done.
Writing objects: 100% (47/47), 9.44 KiB | 568.00 KiB/s, done.
Total 47 (delta 24), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (24/24), done.
```
# Exercise 3
```bash

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git checkout -b ft/footer
Switched to a new branch 'ft/footer'

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/footer)
$ git add footer.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/footer)
$ git commit -m 'add a footer pages'
[ft/footer d1a603c] add a footer pages
 1 file changed, 11 insertions(+)
 create mode 100644 footer.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/footer)
$ git git add footer.html
git: 'git' is not a git command. See 'git --help'.

The most similar command is
        init

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/footer)
$ git add footer.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/footer)
$ git commit -m 'Update footer pages with new location'
[ft/footer 10feee4] Update footer pages with new location
 1 file changed, 2 insertions(+), 1 deletion(-)

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/footer)
$ git push -u origin ft/footer
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 715 bytes | 715.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/evariste060/Gym-Git-Exercise-solution/pull/new/ft/footer
remote:
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
 * [new branch]      ft/footer -> ft/footer
branch 'ft/footer' set up to track 'origin/ft/footer'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/footer)
$ git push -u git-copy ft/footer
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 16 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (9/9), 1.33 KiB | 1.33 MiB/s, done.
Total 9 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/evariste060/Gym-Git-Exercise-solution2/pull/new/ft/footer
remote:
To https://github.com/evariste060/Gym-Git-Exercise-solution2.git
 * [new branch]      ft/footer -> ft/footer
branch 'ft/footer' set up to track 'git-copy/ft/footer'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/footer)
$ git checkout main
M       home.html
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (main)
$ git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/squashing)
$ git merge -squash ft/footer
Could not find merge strategy 'quash'.
Available strategies are: octopus ours recursive resolve subtree.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/squashing)
$ git merge --squash ft/footer
Updating 470a6c4..10feee4
Fast-forward
Squash commit -- not updating HEAD
 footer.html | 12 ++++++++++++
 1 file changed, 12 insertions(+)
 create mode 100644 footer.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/squashing)
$ git status
On branch ft/squashing
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   footer.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html


user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/squashing)
$ git commit -m 'footer changes squashing'
[ft/squashing 47b22ca] footer changes squashing
 1 file changed, 12 insertions(+)
 create mode 100644 footer.html

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/squashing)
$ git push -u origin ft/squashing
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 459 bytes | 459.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/evariste060/Gym-Git-Exercise-solution/pull/new/ft/squashing
remote:
To https://github.com/evariste060/Gym-Git-Exercise-solution.git
 * [new branch]      ft/squashing -> ft/squashing
branch 'ft/squashing' set up to track 'origin/ft/squashing'.

user@LAPTOP-300LKL1I MINGW64 ~/git-exercise (ft/squashing)
$ git push -u git-copy ft/squashing
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 459 bytes | 459.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/evariste060/Gym-Git-Exercise-solution2/pull/new/ft/squashing
remote:
To https://github.com/evariste060/Gym-Git-Exercise-solution2.git
 * [new branch]      ft/squashing -> ft/squashing
branch 'ft/squashing' set up to track 'git-copy/ft/squashing'.

```














