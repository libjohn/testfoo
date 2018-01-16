# README

This is a test repo to practice @mozadrella's git workshop.

@mozzadrella showed us some really cool stuff:

Here are the things I might have the most trouble remembering.  More detail in the [notes](notes.md)

> git remote
  
> git remote add <<origin>> (REPO LOCATION)
  
> git remote add mirror-dvs https://github.com/data-and-visualization/mozadrella-test.git
  
> git push -u mirror-dvs master
  
- `-u` identifies the default remote
      
> git remote -v
  
> git show master

## Procedure:  To Mirror an Existing GitHub Repo to DVS

1. Goto the Social Coding Hub where you want to push your repo
1. Create the Repo in the cloud

    - no need for .gitignore, license, or README because you are mirroring a repo.
    
1. In the Newly created remote Repo > Settings > Collaborators
1. Add a Collaborator
1. Collaborator inviatation via email needs to be accepted
1. Return to original local Repo
1. Add a remote with the location pointer generated at the social-hub
1. git push <mirror-repo-name> master
  
  
  
  
  
  
  
 