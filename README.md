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

## Initialize Repository:
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
