# Charlie First Repo 4/18/23

## Process
Clone the github repo
- $ `git clone https://github.com/learn-academy-2023-charlie/charlie-first-repo.git`

cd into that repo
- $ cd charlie-first-repo

Created a branch
- naming convention:
`<topic>-<initials>-<initials>`
- $ git checkout -b first-repo-cb

Informational command to see which branch you are on (* marks the branch)
- $ git branch

Open the text editor
- $ code .

Informational command to see all files/folders in the repo
- $ ls

Informational command to see all files/folders plus the hidden ones in the repo
- $ ls -a

Create a file
- naming convention:
`<topic>-<name>-<name>.<extension>`
- $ touch first-repo-charlean.md

## pushing changes from the local repo to github (remote repo)
- $ git status
- $ git add <file-name>
- $ git commit -m "meaningful message"
- $ git push origin <branch-name>

## Switching drivers
Clone the repo
- $ `git clone https://github.com/learn-academy-2023-charlie/charlie-first-repo.git`

cd into the repo
- $ cd charlie-first-repo

Informational command to see which branch you are on (* marks the branch)
- $ git branch

Get access to the branch that is on github
- $ `git fetch origin <branch-name>`

checkout the branch
- $ `git checkout <branch-name>`

Informational command to see which branch you are on (* marks the branch)
- $  git branch

To see all terminal commands you have ran
- $ history
Open text editor to make changes
- $ code .

## Branch is on local machine
- $ `git pull origin <branch-name>`

## Creating a pull request
Follow instructions for [Merging to Main on Github](https://github.com/learn-academy-2023-charlie/Syllabus/blob/main/github/pairing-with-github.md) from syllabus

# Branch

## Deleting stale branches locally
- $ git checkout main
- $ git pull origin main
- $ `git branch -d <branch-name>`
