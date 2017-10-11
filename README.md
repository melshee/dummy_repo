# dummy_repo

making a new branch:
git branch [name of new branch]

list branches
git branch

checkout a branch 
git checkout [anem of branch]

git push --set-upstream origin fixcontent
or
git push -u origin fixcontent
- u == --set-upstream

merging:
from the banch you want to merge INTO: git merge [name of branch u want to merge from]

merging moves the commit u had in one branch to the other branch (so u don't have to _____)
 
if u want to push to another branch aside from master, you migth have to do
git push -u origin [new branch name] in order to allow git to do so

making a branch "upstream" = allowing yourself to push to it
 
 
 
git push: assumes you have write permissions for the repo

in open-source projects, you prob won't have these permissions. Instead you do..
pull request: asks someone with write permissions: "please accept this code I wrote/modified and add it to your repo"
 

