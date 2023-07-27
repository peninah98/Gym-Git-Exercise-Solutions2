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
