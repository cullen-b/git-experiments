# git-experiments

Experimenting with git &amp; Github in advanced software design.

## Part 1

1) git clone <my repo link/my partners repo link>
2) nvim newfile.txt
3) fill and save my new file
4) git add .
5) git commit -m "<my commit message>"
6) git push
7) go to Github and check to see if my file is there (it was!).

To get my partners file

1) git pull
2) open the new file and see what is in it!
3) go to github and make sure both of our changes are online

John Hurtubise:
All of the process were the exact same except I used "nano" as the text editor
and I checked git status after my commit.

## Part 2

1) Used "git branch johnBranch" to create new branch
2) touch <filename>.txt to create new text file
3) nano <filename>.txt to edit file
4) Used "git checkout johnBranch" to move to new branch
5) git add <filename>.txt to start tracking file
6) git commit -m "<message>" to commit changes
7) "git push --set-upstream origin johnBranch" to connect branch to origin branch
 and push changes.
8) Used gitHub to create new pull request.
9) Added notes to readme and pushed to origin.

Cullen - everything was the same for me!

## Part 3

1) I changed johnNewFile.txt
2) then added, commited, and pushed
3) Now if we go and edit johnNewFile.txt before pulling we will have a merge conflict!
4) "git config pull.rebase false" to merge the files
5) then "git pull" to merge
6) "git push" to push the merge to github

John Hurtubise
1) I added a new file conflictFile.txt with inital text and added, 
committed, then pushed.
2) I then made changes localy without pushing them to gitHub. 
3) Now if cullen makes changes and I try to pull it will cause a conflict
4) Now to fix the conflict we have to git merge and manually fix the 
merge conflicts

 
