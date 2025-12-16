
https://www.youtube.com/watch?v=RGOj5yH7evk

i was a noob just uploading files on github chrome and not using terminal. im changing it today. 16/12/25

what is git--- version control system, we programmers can track our code changes

git terminal >>>> git desktop/kraken

some basic git nerd terms

git ---> refers to your project tracker
github ---> website where we host our git repos
![[Screenshot 2025-12-16 at 6.50.39 PM.png]]
![[Screenshot 2025-12-16 at 6.58.58 PM.png]]

repository ---> basically your project

contains all folders files regarding the project

commits ---> snapshot of your project like a save point


![[Screenshot 2025-12-16 at 7.06.45 PM.png]]

here we can see after a commit, the green shows the update, the red was deleted, the white stayed the same
![[Screenshot 2025-12-16 at 10.10.44 PM.png]]



![[Screenshot 2025-12-16 at 9.42.13 PM.png]]
![[Screenshot 2025-12-16 at 9.42.29 PM.png]]

![[Screenshot 2025-12-16 at 9.42.53 PM.png]]

![[Screenshot 2025-12-16 at 10.11.24 PM.png]]
![[Screenshot 2025-12-16 at 10.11.39 PM.png]]
==============================
GIT CHEAT SHEET (MINIMAL)
==============================

ONE-TIME SETUP
--------------
git config --global user.name "Your Name"
git config --global user.email "you@email.com"


CLONE A REPO
------------
git clone git@github.com:username/repo.git
cd repo


DAILY WORKFLOW (MOST IMPORTANT)
-------------------------------
git status
git diff
git add .
git commit -m "short meaningful message"
git push origin main


PULL BEFORE WORKING
-------------------
git pull origin main


ADD FILES / FOLDERS
-------------------
git add file.v
git add folder/


EMPTY FOLDER FIX
----------------
touch folder/.gitkeep
git add .


UNDO MISTAKES
-------------
Unstage:
git restore --staged file.v

Discard changes:
git restore file.v


VIEW HISTORY
------------
git log --oneline


BRANCHES (OPTIONAL)
-------------------
git branch
git checkout -b new_branch
git checkout main


CHECK SSH
---------
ssh -T git@github.com


OPEN REPO
---------
open .
code .


MENTAL MODEL
------------
Working dir -> git add -> git commit -> git push


ABSOLUTE MINIMUM
----------------
git status
git add .
git commit -m "msg"
git push origin main