# Git Commands
===========================

Below are the commanly used git commands

## First Step:
  `Navigate to the folder you want or execute the below command.`
  Steps: 
    
      1. md NewRepo
      2. cd NewRepo
      3. start . (It will open the window in explorer)
      4. Right click and select "GIT GUI Bash Here"

## Help:
    git help

## Config:
    git config --global user.name "SriniVasanB"
    git config --global user.email "sritechnoo@gmail.com"
    git config -l
    git config --global --unset user.password 

## Remove files not managed by Git.:
    git clean -df 
    git clean -df 
    git -n clean 
    git -dn clean

## Cloning Remote Repository (Creates a local copy of remote repostiory):
    git clone ssh://git@github.com/<User_Name>/<Repo_Name>.git

## Initialize Local Repository:
    git init <Repo_Name>

## Check Status:
    git status

## Add files from UnTrack Area to Staging Area:
    git add README.md
    git add .
    git add -A
    git add --all

## Revert files from Staging Area to UnTrack Area:
    git rm -r --cached README.md = File only removed from the staging area
    git rm -r --cached -f README.md = File removes in both places staging area and disk

## Commit files Staging Area to Repository:
    git commit -m "<Commit_Message>"

## View Commit History:
    git log
    git log --summary
    git log --oneline 
    git log directory/path/file 
    git log --author="name" 
    git log --graph --decorate --oneline

## Branching:
  ### List Branch (local only):
    git branch 
  ### List all Branch (remote and local):
    git branch -a 
  ### Create a Branch:
    git branch <Branch_Name> 
  ### Delete a Branch:
    git branch -d <Branch_Name> 
  ### Switch to a Branch:
    git checkout <Branch_Name>     
  ### Create and Switch to a Branch:
    git checkout -b <Branch_Name>      
  ### Merging from branch:
    git merge <Branch_Name>