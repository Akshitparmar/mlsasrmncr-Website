# mlsasrmncr-Website
A website for MLSA SRM NCR 

# How to contribute
1. You can contribute in terms of Code
2. You can contribute in terms of improving Documentation
## Following the procedure you can make your contribution with ease.

### Step 1
Look in the issues if the change you are doing is available and issues section is it assigned to someone or not if you can't find any issue open one. Anyone from our team will assign you the issue then you can start contributing

### step 2 Fork this repository
You can fork this repository by clicking on fork button on top right corner. Once you fork this will create a copy of repo on your account

### step 3 Clone the repository 
To clone the repository go to your account open this repo and either click on clone button or run the command below to get this repository on your local machine

> git clone "URL you just copied"
e.g. git clone https://github.com/mlsasrmncr/mlsasrmncr-Website/

> Configure remotes: (Important)

`git remote add upstream https://github.com/mlsasrmncr/mlsasrmncr-Website`

### step 4 Create a branch
On your local machine go the project folder that you cloned and use following git command inside that folder

create a new branch using below command.

> git checkout -b \<branch-name\>
e.g. `git checkout -b mybranch`

### step 5 Lets make some contributions
Make changes to files on your local machine work on the issue you're assigned. 

### step 6 Add Changes and Commit Changes
Now we have to add changes that we made to the branch so for that we will run following command.

> git add .

Now we have to commit changes, commit message should always be clear, to commit use command below 

*NOTE:- Always add the issue number in your commit for easyness and also mention the issue no (eg. #345) in the description of the pull request. And alwas push something under a issue only.*

> git commit -m "resolved the \<issue\>"

### step 7 Push changes to GitHub
Now we have to push the changes that we made to remote repository on specified branch to do so use command below.

> git push origin \<branch-name\>
name of branch is same as you created in step 3

e.g `git push origin mybranch`

### step 8 Repeat steps 5-7 till development is complete
All additional commits, please [squash to first](https://davidwalsh.name/squash-commits-git)

>e.g:
```
git rebase -i main
git push --force origin <branch name>
```
### step 9 Update current branch and local master by pulling changes that were done by other contributors:
>e.g:
```
git checkout main
git pull upstream main
git push origin main
```

### step 10 Rebase your branch over your updated master
>e.g:
```
git checkout <bramch name>
git rebase main
```
>In the process of the rebase, it may discover conflicts.
In that case it will stop and allow you to fix the conflicts.
After fixing conflicts, use git add . to update the index with those contents,
and then just run:
>e.g:
`git rebase --continue`

### step 11 Push branch to GitHub
>e.g:
`git push --force origin my-new-check`

### step 12 Submit your changes for review
Once you have pushed your code to GitHub, it's now time to create pull request, you will go to the repository click on compare and pull request and submit the pull request.

Soon, we will be merging all your pull requests to the main branch of project and you will also get notification once your pull request is merged with existing code base. After that you will be able to see your details in contributor section on the page below.
