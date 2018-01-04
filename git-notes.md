# Notes on Using git #

## git

Everything starts with the `git` command

## commit

`git commit`

  Save a new version of what I'm working on
  
## branch
  
`git branch [newBranchName]`
  
  A 'branch' points to a specific commit that contains the current work and all of the parent work.
  
## checkout
  
`git checkout [branchName]`
  
  By doing a 'checkout' you are 'on' the named branch, rather than the master when performing new commits
  
*****
  
You can create a new branch AND check it out at the same time...
  
  `git checkout -b [newBranchName]`
  
*****

## merge

`git merge [branchName]`

Adds the work in the branch to the master

## rebase

`git rebase`

Moves the master and the branch to the same path(?)

## log

`git log`

*You only have to type enough of the leading characters of the hash to recognize that it is unique*



