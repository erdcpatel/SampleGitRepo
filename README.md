# Sample Git Commands

echo "# SampleGitRepo" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/erdcpatel/SampleGitRepo.git

git push -u origin master

	
## Copy all the other files:

git add .

it commit -m 'Initial Commit'

git push



## Create the branch on your local machine and switch in this branch :
$ git checkout -b [name_of_your_new_branch]


## Change working branch :

$ git checkout [name_of_your_new_branch]


## Push the branch on github :

$ git push origin [name_of_your_new_branch]


## You can see all branches created by using :

$ git branch

## First, you should create a commit that removes this folder from git:
$ git rm -r bin

$ git commit -m "Removed bin folder"

$ git push origin master


## adding the bin directory to your .gitignore file, and commit that change too:
$ echo "bin/" >> .gitignore

$ git add .gitignore

$ git commit -m "Added bin folder to gitignore"

$ git push origin master

## In Case your password updated:
git config credential.helper store


## Merge Staging to Master :

git checkout staging

git merge master

git status

git push 

git push --set-upstream origin staging

## Merge Master to Master :

git checkout master

git merge staging

git status

git push
