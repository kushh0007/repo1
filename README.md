# repo1
NEW FILE AND COMMITING 
D :
Cd Kushala 
cd gitlab
mkdir local repo
git init
cd Local repo 
git add file l. txt
git commit -m "file l created" 
git log
git add file 2. txt 
git commit -m "file 2 created" 
git add file 3.txt
git commit -m "file 3 created" 
git log

BRANCHING 
D:
cd Kushala 
cd gitlab
mkdir local repo
git init 
cd local repo
git add filel. txt
git commit -m "file 1 created" 
git checkout -b featurebranch 
git add file l. txt
git commit - m "modified file 1" 
git checkout master 
git merge featurebranch
git branch --delete feature branch

STASH AND SWITCHING BRANCH 
D:
cd Kushala
cd gitlab 
mkdir local repo
git init 
cd local repo
git add file 2.txt
git commit -m "file 2 created"
git checkout -b Sourcebranch 
file 2. txt
git stash save "file 2 modified" 
git checkout -b targetbranch 
git stash apply 
git add file2. txt
git commit -m "file 2 updated"  
file 2.txt
git Checkout master 
file 2. txt 
git merge targetbranch
file1.txt
git branch -- list 
git stash list
git stash drop Stash @ {o}

CLONING 
d:
cd kushala
cd gitlab
git init
git clone (http//repo paste)

REBASE
D :
git init 
git clone 
cd repo l
git checkout - b fb 
git fetch origin 
git rebase origin 
git add README. md
git commit -m "modified local machine "
git fetch origin 
git rebase origin 
git add README.md 
git rebase -- Continue 
git push origin fb

MERGING FEATURE BRANCH 
git checkout main
git merge fb1

CREATING TAGS 
d:
git init
git add file l. txt 
git commit -m "file created" 
get checkout -b fb 
git add file l. txt
git commit -m "add functionality"
git add file l. txt
git commit -m "sub functionality"
git tag v1.0
git log
git add file l. txt
git commit -m "mul functionality"
git add file l. txt 
git commit -m "div functionality"
git tag v2.0
git log 
git tag -l
git tag -d V1.0
git tag -d v2.0
git tag V1.0(commit id-mul)
git tag v2.0 (commit id-div)
git log 

CHERRY PICK
git init
git add file 1. txt 
git commit -m "file l created" 
git checkout -b fb
git add file 1. txt 
git commit -m " fbl"
git add file 1. txt
git commit -m " fb2"
git add file 1. txt 
git commit -m " fb3"
git add file 1. txt 
git commit -m " fb4"
git add file 1. txt 
git commit -m " fb5"
git add file 1. txt 
git commit -m " fb6"
git log 
git checkout master 
git checkout -b tb
git cherry-pick (last commit id ^.. 1stcommit id)
git add file 1. txt
git cherry-pick -- continue
git add file 1. txt
git cherry-pick -- continue
git log

HISTORY
git tag V1.0(Cid-add)
git tag v2. 0 (cid-master)
git log
git show (cid-sub)
git log -n2 (cid-add)

BTW 2 DATES
git log --author="kushala"--since="2024-03-19"--until="2024-03-20"

LAST 5 COMMITS 
git init
git add file l.txt
git commit -m "1st commit"
git add file 1. txt 
git commit -m "2nd commit"
git add file 1. txt 
git commit -m "3rd commit"
git add file 1. txt 
git commit -m "4th commit"
git add file 1. txt 
git commit -m "5th commit"
git add file 1. txt 
git commit -m "6th commit"
git add file 1. txt 
git commit -m "7th commit"
git log -n5

UNDO CHANGES
git revert(cid-7th)
git log -n5










