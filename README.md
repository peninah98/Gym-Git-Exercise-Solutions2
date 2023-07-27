# Gym-Git-Exercise-Solutions2
## Bundle 1
### Exercise 1

```

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)      
$ git branch -m master main
fatal: No branch named 'master'.

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)      
$ touch index.html

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)      
$ git add .

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)
$ git commit -m 'Exercise 1 of Bundle 1'
[main 5c8477b] Exercise 1 of Bundle 1
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)      
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 287 bytes | 95.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/peninah98/Gym-Git-Exercises.git
   39015e1..5c8477b  main -> main

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)      
$ git checkout -b dev
Switched to a new branch 'dev'

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)       
$ git checkout -b test
Switched to a new branch 'test'

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (test)      
$ git checkout dev
Switched to branch 'dev'

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git branch -d test
Deleted branch test (was 5c8477b).

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git branch
* dev
  main

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)



   9  git branch -m master main
   10  touch index.html
   11  git add .
   12  git commit -m 'Exercise 1 of Bundle 1'
   13  git push
   14  git checkout -b dev
   15  git checkout -b test
   16  git checkout dev
   17  git branch -d test
   18  git bra

```



### Exercise 2
```
User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ touch home.html

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git add .

 create mode 100644 home.html

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash
No local changes to save

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash
No local changes to save

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash save
No local changes to save

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git status
On branch dev
nothing to commit, working tree clean

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git status
On branch dev
nothing to commit, working tree clean

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)
$ git checkout dev
Switched to branch 'dev'

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git status
On branch dev
nothing to commit, working tree clean

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git status
On branch dev
nothing to commit, working tree clean

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git status
On branch dev
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    home.html

no changes added to commit (use "git add" and/or "git commit -a")

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git status
On branch dev
nothing to commit, working tree clean

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ gti stash
bash: gti: command not found

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash
No local changes to save

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
On branch dev
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 2345ffc Home page

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash list
stash@{0}: WIP on dev: 2345ffc Home page

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ touch about.html

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash
No local changes to save

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git status
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html

nothing added to commit but untracked files present (use "git add" to track)

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash
No local changes to save

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git add .

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 2345ffc Home page

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ touch team.html

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git add .

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 2345ffc Home page

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash list
stash@{0}: WIP on dev: 2345ffc Home page
stash@{1}: WIP on dev: 2345ffc Home page
stash@{2}: WIP on dev: 2345ffc Home page

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash restore stash@{1}
fatal: subcommand wasn't specified; 'push' can't be assumed due to unexpected token 'restore'

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (4c64d4449a51eb4bd7e7724ce84922c4def7be7e)

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git add .

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git commit -m'Restored file from stash"
>
> ^C

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git commit -m'Restored file from stash'
[dev a53e716] Restored file from stash
 1 file changed, 11 insertions(+)
 create mode 100644 about.html

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$  git push --set-upstream origin dev
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 677 bytes | 135.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/peninah98/Gym-Git-Exercises/pull/new/dev
remote:
To https://github.com/peninah98/Gym-Git-Exercises.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped stash@{0} (64d46bfbeb8b38469bef3b94092428adc6de1c8b)

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git reset

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)


 git branch -d test
   18  git branch
   19  history
   20  touch home.html
   21  git add .
   22  git commit -m 'Home page'
   23  git stash
   24  git stash
   25  git stash save
   26  git status
   27  git status
   28  git checkout main
   29  git status
   30  git checkout dev
   31  git status
   32  git status
   33  git status
   34  git status
   35  gti stash
   36  git stash
   37  git stash
   38  git status
   39  git stash
   40  git stash list
   41  touch about.html
   42  git stash
   43  git status
   44  git stash
   45  git add .
   46  git stash
   47  touch team.html
   48  git add .
   49  git stash
   50  git stash list
   51  git stash restore stash@{1}
   52  git stash pop stash@{1}
   53  git add .
   54  git commit -m'Restored file from stash"

   55  git commit -m'Restored file from stash'
   56  git push
   57   git push --set-upstream origin dev
   58  git stash pop stash@{0}
   59  git reset
   60  history
```


## Bundle 2
### Exercise 1

```
User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git branch ft/bundle-2

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git branch
* dev
  ft/bundle-2
  main

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ touch services.html

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git add .

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
 create mode 100644 services.html
 create mode 100644 team.html

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 458 bytes | 458.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/peninah98/Gym-Git-Exercises.git
   a53e716..f68cbda  dev -> dev

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$

```
### Exercise 2

```

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (dev)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)
$ git pull
Already up to date.

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'


User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ touch service.html

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ git add .

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ git commit -m'Service page'
[ft/service-redesign 10e37c4] Service page
 1 file changed, 12 insertions(+)
 create mode 100644 service.html

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use    

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking 
upstream, see 'push.autoSetupRemote' in 'git help config'.        
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 494 bytes | 494.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/peninah98/Gym-Git-Exercises/pull/new/ft/service-redesign
remote:
To https://github.com/peninah98/Gym-Git-Exercises.git
 * [new branch]      ft/service-redesign -> ft/service-redesign   
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
bash: ggit: command not found

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)
$ git pull
Already up to date.

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)
$ ls -la
total 13
drwxr-xr-x 1 User 197121  0 Jul 27 20:55 ./
drwxr-xr-x 1 User 197121  0 Jul 27 14:55 ../
drwxr-xr-x 1 User 197121  0 Jul 27 20:56 .git/
-rw-r--r-- 1 User 197121  0 Jul 27 11:52 index.html
-rw-r--r-- 1 User 197121 19 Jul 27 11:11 README.md

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)
$ git branch
  dev
  ft/bundle-2
  ft/service-redesign
* main

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (main)
$ git checkout ft/service-redesign 
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ ls -la
total 14
drwxr-xr-x 1 User 197121   0 Jul 27 21:03 ./
drwxr-xr-x 1 User 197121   0 Jul 27 14:55 ../
drwxr-xr-x 1 User 197121   0 Jul 27 21:03 .git/
-rw-r--r-- 1 User 197121   0 Jul 27 11:52 index.html
-rw-r--r-- 1 User 197121  19 Jul 27 11:11 README.md
-rw-r--r-- 1 User 197121 282 Jul 27 21:03 service.html

cises (ft/service-redesign)
$ git merge ft/service-redesign
Already up to date.

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$  git diff

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ git status
On branch ft/service-redesign
Your branch is up to date with 'origin/ft/service-redesign'.

nothing to commit, working tree clean

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ git checkout ft/service-redesign 
Already on 'ft/service-redesign'
M       service.html
Your branch is up to date with 'origin/ft/service-redesign'.

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ git diff
diff --git a/service.html b/service.html
index e6505a5..09a7e45 100644
--- a/service.html
+++ b/service.html
@@ -7,6 +7,7 @@
 </head>
 <body>
     <h1>Git Exercise Bundle 2 Exercise 2 || Service page</h1>
+    <p> This is the service page for Git exercise bundle.<br></p>      

 </body>
 </html>
\ No newline at end of file

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ git merge main
Already up to date.

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        service.html
Please commit your changes or stash them before you switch branches.    
Aborting

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ git add .

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ git commit -'Merged changes'
error: unknown switch `M'
usage: git commit [-a | --interactive | --patch] [-s] [-v] [-u<mode>] [--amend]
                  [--dry-run] [(-c | -C | --squash) <commit> | --fixup [(amend|reword):]<commit>)]
                  [-F <file> | -m <msg>] [--reset-author] [--allow-empty]
                  [--allow-empty-message] [--no-verify] [-e] [--author=<author>]
                  [--date=<date>] [--cleanup=<mode>] [--[no-]status]    
                  [-i | -o] [--pathspec-from-file=<file> [--pathspec-file-nul]]
                  [(--trailer <token>[(=|:)<value>])...] [-S[<keyid>]]  
                  [--] [<pathspec>...]

    -q, --quiet           suppress summary after successful commit      
    -v, --verbose         show diff in commit message template

Commit message options
    -F, --file <file>     read message from file
    --author <author>     override author for commit
    --date <date>         override date for commit
    -m, --message <message>
                          commit message
    -c, --reedit-message <commit>
                          reuse and edit message from specified commit  
    -C, --reuse-message <commit>
                          reuse message from specified commit
    --fixup [(amend|reword):]commit
                          use autosquash formatted message to fixup or amend/reword specified commit
    --squash <commit>     use autosquash formatted message to squash specified commit
    --reset-author        the commit is authored by me now (used with -C/-c/--amend)
    --trailer <trailer>   add custom trailer(s)
    -s, --signoff         add a Signed-off-by trailer
    -t, --template <file>
                          use specified template file
    -e, --edit            force edit of commit
    --cleanup <mode>      how to strip spaces and #comments from message
    --status              include status in commit message template     
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit

Commit contents options
    -a, --all             commit all changed files
    -i, --include         add specified files to index for commit       
    --interactive         interactively add files
    -p, --patch           interactively add changes
    -o, --only            commit only specified files
    -n, --no-verify       bypass pre-commit and commit-msg hooks        
    --dry-run             show what would be committed
    --short               show status concisely
    --branch              show branch information
    --ahead-behind        compute full ahead/behind values
    --porcelain           machine-readable output
    --long                show status in long format (default)
    -z, --null            terminate entries with NUL
    --amend               amend previous commit
    --no-post-rewrite     bypass post-rewrite hook
    -u, --untracked-files[=<mode>]
                          show untracked files, optional modes: all, normal, no. (Default: all)
    --pathspec-from-file <file>
                          read pathspec from file
    --pathspec-file-nul   with --pathspec-from-file, pathspec elements are separated with NUL character


User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ git commit -m 'Merged changes'
[ft/service-redesign b5845f0] Merged changes
 1 file changed, 1 insertion(+)

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 361 bytes | 361.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.   
To https://github.com/peninah98/Gym-Git-Exercises.git
   10e37c4..b5845f0  ft/service-redesign -> ft/service-redesign

User@DESKTOP-TTE4MSC MINGW64 ~/Desktop/The Gym/Gym-Git-Exercises (ft/service-redesign)
```
