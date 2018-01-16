NOTES

2018-01-16

slide deck launches on Feb 21.  

## Commands

- git --version
- git config user.name
- git config global user.email
- git init exercise-1


1. touch README.md
2. git status
3. git add README.md
4. git status
5. git commit -m "my special commit message"1. 
1. git status

### Build an Exercise for the Workshop



1. git status
1. edit README2.md 
1. save README2.md
1. git status
1. git diff
1. git add README2.md
1. git diff --staged
1. git log
1. touch slides-1.html
1. touch slides-2.html
1. git **reset** slides-2.html
1. edit slides-1.html
1. git status (reports different stages of slides-1.html)
1. git commit -m "add html to slides1.html"
1. git status
1. git add slides-1.html
1. git commit -m "fixed html"
1. git status

### Three fold model

- working directory
- staging area
- repository



## Definitions

- Repository:  an entire history of projects

## Thoughts

- one repository per student / per assigment
- .git :: the whole project lives in here consisting of compressed files


### Mental Model of Git

metaphor is of a writer's desk with a:

- workspace
- file staging area
- published file storage area

job of the staging area is to bridge the gap between the working space and the project history.  git users *should work towards a meaningful commit*.  

- git add :: to stage changes between drafts


## Network Activity (Exercise #2) 

moving to GitHub

### Remotes

- Dr. Root with a class of vegatables

- **`git remote add <<origin>> (REPO LOCATION)`**

1. git remote
1. git remote add 

    - git remote add mirror-dvs https://github.com/data-and-visualization/
mozadrella-test.git

1. git remote
1. git push -u mirror-dvs master

    - **u** stands for *upstream*
    - go into the mirror-dvs settings
    - add collaborator
    - then ...

1. git remote -v

**NOTE** the -u will identify the default remote 

- git show master

## Hackathons

https://education.github.com/pack
https://githubcampus.expert 
https://internships.github.com



