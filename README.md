PS D:\Manasvi\SE> git init
Initialized empty Git repository in D:/Manasvi/SE/.git/

PS D:\Manasvi\SE> git config --global user.name "manasvik2006"
PS D:\Manasvi\SE> git config --global user.email "kmanasvigithub03@gmail.com"
PS D:\Manasvi\SE> git remote add origin https://github.com/manasvik2006/SE.git

git checkout -b master

PS D:\Manasvi\SE> git pull origin master
From https://github.com/manasvik2006/SE
 * branch            master     -> FETCH_HEAD
Already up to date.it commit -m "Added app.py"

PS D:\Manasvi\SE> git checkout -b "feature"
Switched to a new branch 'feature'

PS D:\Manasvi\SE> git add .
PS D:\Manasvi\SE> git commit -m "Added feature"
[feature 4380a8c] Added feature
 1 file changed, 1 insertion(+)one.
PS D:\Manasvi\SE> git checkout masterads
Switched to branch 'master'2/2), done.
Your branch is up to date with 'origin/master'. KiB/s, done.
PS D:\Manasvi\SE> git merge feature0), pack-reused 0 (from 0)
Updating 0a9054c..4380a8casvik2006/SE.git
Fast-forwardch]      master -> master
 app.py | 1 +r' set up to track 'origin/master'.
 1 file changed, 1 insertion(+)
 
PS D:\Manasvi\SE> git push origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 333 bytes | 333.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/manasvik2006/SE.git
   0a9054c..4380a8c  master -> master
   
PS D:\Manasvi\SE> cd D:\Manasvi
PS D:\Manasvi> git clone https://github.com/manasvik2006/SE.git SE-clone
Cloning into 'SE-clone'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 1), reused 5 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.
Resolving deltas: 100% (1/1), done.

PS D:\Manasvi> cd SE-clone
PS D:\Manasvi\SE-clone> dir


    Directory: D:\Manasvi\SE-clone


Mode                 LastWriteTime         Length Name                                                                                                  
----                 -------------         ------ ----                                                                                                  
-a----        08-10-2026  06.23 PM            115 app.py                                                                                                


PS D:\Manasvi\SE-clone> 
 *  History restored 

PS D:\Manasvi\SE> 
