
# Revisions and the Cloud

##### 6/22/22 - Code 102 - Day Three

Today I learned about Git, the software underneath Github. I learned that it is a way to collaborate with others on the same project, save your work, and prevent problems from arising during the process. I learned some basic Git terminal commands, such as:

* `git clone` - Clones the repository
* `git add .` - Adds all the files changed that are to be tracked by Git
* `git commit -m 'message here'` - Commits changes
* `git push origin main` - Sends changes to Github
* `git status` - Lets your know the standing of modified files and whether they are staged to be committed or not, or if there are commits needing to be pushed
* `git stash` - Allows you to temporarily hide changes you're not ready to commit

I also learned how to set up Git in the terminal. I had difficulty with the Github authentication today, but luckily a TA was able to help me sort it out! Here are some notes from the reading:

* Version Control Systems help to record changes throughout the process of a project, so that mistakes can be fixed easily.
* Git's the most popular VCS in the world
* Distributed Version Control Systems, like **Git**, allow for multiple mirrored repositories to prevent data loss and allow for teams to collaborate and complete joint projects.
* What Git is:
  * Snapshots
  Saved references of your work every time it is saved (/committed)
  * Local Operations
  A project history is saved to a local disk as opposed to calling on a server for it
  * Tracking Changes
  Every change is tracked, which helps detect file issues
  * Loss of Data
  Highly difficult for snapshots to be lost
  * States
    * _Committed_
      Stored in local database
    * _Modified_
      Changed but not committed
    * _Staged_
      Flagged a file's changed version to be comitted in the next snapshot
* Workflow
  * _Working Directory_
  The actual files reside here
  * _Index_
  The area for staging
  * _Head_
  Points to the most recent commit

## Lecture Notes

* git lives on your machine
* github is on the web
* git is used for sharing code
* git lets multiple devs work on the same code
* repository is really just a folder
* helps with collaboration
* commits are snapshots in time of the document
* 'head' current state, where you're at, all else is historical
* you give the snapshot a label called a message
* github is not git. you push your code to github. effectively an online backup.
* uses git's features to help manage work
* a repo is is a collection of files you've told git to pay attention to
* one project = one repo, usually
* really large projects might have multiple repositories for different parts of their system
* repos can live on github and/or computer

[Table of Contents](https://kvvpa.github.io/reading-notes/)
