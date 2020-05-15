# Git cheating sheet

## What is version control ?
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.

## What is Git ?
Git is distributed version control system that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it.

## What is GitHub ?
GitHub provides hosting for software development version control using Git.

## How to import existing directory into Git repo ?
1. switch to the directory <br/>
`cd test`
2. initialize local git repo <br/>
`git init`
3. start tracking all the repository files <br/>
`git add .`
4. create a commit -**version or snapshot**- of the repo <br/>
`git commit -m "first commit"`

## Cloning
You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:
```
$ git clone https://github.com/test
```
## How to import manual Cloud repo, rather than cloning ?
1. create a directory for the new repo <br/>
`mkdir repo`
2. initialize local git repo <br/>
`git init`
3. add the origin(**link**) for the repo <br/>
`git remote add origin https://github.com/test`
4. pull the hosted repo files <br/>
`git pull origin master`

## synchronize change with cloud repo - **ACP**
1. stage (track) the modified file <br/>
`git add test.js`
2. create a commit -**version or snapshot**- of the repo <br/>
`git commit -m "chnage of test.js"`
3. push to the change to cloud repo <br/>
`git push origin master`
