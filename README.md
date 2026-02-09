//after dwonload
git --version
config --global user.name "satish gupta"
git config --global user.email "satish20**@gmail.com"
git config --list


👉 git add = batana “ye change save karna hai” (staging area)
👉 git commit = “ab permanently save kar do” (History add parament)"my first

//⭐ how to assign a folder/file
1) git init

#initally all untrack rahta h 
 track krne k liye  ✅ git add filename
 for all ,use this cmd ✅ git add .
 to see change file    ✅  git status 
 
 //what is commit 
 to commit all fie use this cmd ✅ git commit -m "my first commit"
 
 
⭐ to see actual change code = git diff , use q cmd fpr exiting

if you want to remove some from staging use this cmd  ✅git reset first.js 


🔹 What is git log?
git log is used to see the commit history of a repository.
It shows:Commit ID (SHA),Author,Date,Commit message
👉 In short: “Project ka pura history”

commit 0d3cf0ce31800eb28afe65e14875127495226783 (HEAD -> master)    
Author: satish gupta <satish202627@gmail.com>
Date:   Sun Feb 8 11:45:50 2026 +0530

   git third commit

commit fa79414f0c6281c88337d58b40b4f0a016c5f7e7
Author: satish gupta <satish202627@gmail.com>
Date:   Sun Feb 8 11:44:52 2026 +0530

    this is second commit

commit 79fc6fbe0b85dd7450c8e64309e496ad46e3ecba
Author: satish gupta <satish202627@gmail.com>
Date:   Sun Feb 8 11:42:51 2026 +0530
||
(short)
👍git log --oneline
0d3cf0c (HEAD -> master) git third commit
fa79414 this is second commit
79fc6fb git  first commit

#📝⭐git show id
git show 0d3cf0c
commit 0d3cf0ce31800eb28afe65e14875127495226783 (HEAD -> master)
Author: satish gupta <satish202627@gmail.com>
Date:   Sun Feb 8 11:45:50 2026 +0530
    git third commit
diff --git a/GitsNew/first.js b/GitsNew/first.js
index 3dab31d..d59c4df 100644
--- a/GitsNew/first.js
+++ b/GitsNew/first.js
@@ -3,4 +3,8 @@ let age=20;
 const balance=300
-const account =20033



What is git reset --hard?
***ye upper wala sb ko hta degs
git reset --hard completely removes changes.
It resets:
✅ Commit (HEAD)
✅ Staging area
✅ Working directory
👉 Meaning: Code + staged + commit = sab clean
//# syntax
git reset --hard <commit-id>
git reset --hard 0d3cf0c
HEAD is now at 0d3cf0c git third commit



git revert = purane commit ka effect hataana,
👉 bina history delete kiye, kyunki naya commit banta hai.
Flow ek line mein:
git revert <hash> → (conflict ho to fix → git add → git revert --continue)



What is a branch?
A branch is a separate line of development.
🔑 Common Commands
git branch              # list branches
git branch feature(name)      # create branch
git checkout feature    # switch branch
git checkout -b feature # create + switch
git branch -d feature   # delete branch

Merge combines one branch into another.
🔑 Command
git merge feature(name)


######GitHub######

   



