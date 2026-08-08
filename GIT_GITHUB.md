# VERSION CONTROL SYSTEM:
-> DISTRIBUTED VERSION CONTROL SYSTEM: DVCS  is on every system, apne laptop mein installed and we can work offline also., without internet (CODE STORE hota ha) LOCAL MACHINE PR CHANGES KRKE CLOUD PR PUSH KIYA on GITHUB.--> OFFLINE AND FAST
-> CENTRALIZED VERSION CONTROL SYSTEM: like internet gya vedio band , online like Tailwin css CDN

# CENTRALIZED VCS handles this both : 
1.VCS
2.STORE/CODE SHARING 
->these both are combined 

# Distributed mein:
1. VCS Local Machine jb kaam hojayega too phr niche code sharing 
2. CODE sharing on cloud ->GITHUB


# GIT IS A DISTRIBUTED VERSION CONTROL SYSTEM.
Git works offline , too isko install krna pdta ha 

# GOOGLE USES "PIPER" AS VERSION CONOTROL SYSTEM.

# mkdir : make directory for making folders and touch filename for making files, rm filename for removing the files.

# mkdir js creates a js folder .
# to delete use rm filename for removing files

# to rmeove folder use: rm -rf foldername where rf is recursively beacuse a folder contains many files also.

# folder -> directory -> repositry (repo) are same . containing files ...

# UP KEY & DOWN KEY ARE IMPORTANT TO SWITCH BETWEEN COMMANDS.


# to set user name: git config --global user.name "Mahi Sharma"
# to set user email: git config --global user.email "mahisharma11a18@gmail.com" 


# to check user name: git config --global user.name
# to check user email:  git config --global user.email


# GIT INIT : used to track the version / history of code , first time and only 1 time to write this. yeh .git krke ek folder banata ha which is hidden folder / repositry

# ls : list all files and folders, here .git is hidden file 
# to check hidden file use: ls -a or ls -la (for permissions and details)

# .git -> repo contains all versions / history, if it is deleted so, verison history also gets deleted.


# ek file se dusri fike mei kaise jaenge:- kaise content dekhe : cat index.html (to see content of the file through terminal)

# command shortcut is cmd


# to see content inside .git folder: first do cd .git
# then do ls or ls -a to see all files then to see content do : cat filename

# pwd (present working directory)
# dusre folde pr jane ke liye ../..

# history stored in => .git folder

-> U is untracked : havinng no version . history not maintained 
-> I don't want one files to be tracked : 

1. WORKING DIRECTORY 
2. STAGING DIRECTORY
3. COMMIT
--> Onine shopping: website pr gaye , searched product and added to cart : item lenin ha ya nhi, then buy or not.

--> Reception party mein ek main stage ha then photographer khada ha , bhid bhi ha agge piche stage ke , photogrpaher clicks photo , photograher ke pas data hoga stage ke aspas wla uske alaga ka kuch bhi nhi... niche wle log are untracked github dont know this --> so photogrpaher as git 

-> so use git add . to get those untracked files to the staging area from working directory. so got U TO A sign where A is Added. 
-> git commit -m "label:meaningfull message" : to add to commit area.
-> commit history :  to check by -> git log : for snapshots.


## git rm --cached index.html: this is used to get files back from tracked to untracked or stagingn to wrokging directoty --> TO CONVERT FROM TRACKED TO UNTRACKED Again.

-> git status: folder ka status to check which files are tracked and hwich not 

## shift+1 and enter to quit vim editor 
# branching , main branch and master branch 

## to see specific git log or history: use git show id ke starting part in commit id 