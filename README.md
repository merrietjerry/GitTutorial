# Git Tutorial - workout
git init<br />
git status<br />
git log<br />
git log --oneline
cat <filename>
touch <filename>
vi <filename>    Esc:wq

vi .gitignore $add gitignore

git add . $add all files
git add <filename> $add specific file
git commit -a -m "<msg>" $to commit all files

git checkout <commit id>    $to go purticular commit
git checkout master     $to go recent
git reset --hard <commit id>   $remove post commits

git branch $list all branches
git branch <branch name> $checkout branch
or 
git checkout -b <branch name>  $create branch and checkout

git checkout <master>   $to branch
git merge <develop>   $from branch


GITHUB

git remote add origin <git url .git>

git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/merrietjerry/GitTutorial.git
git push -u origin master
git push -u origin develop

git pull origin master  $pull file from github

git clone <repo Url>

git --bare init
A bare Git repository is typically used as a Remote Repository that is sharing a repository among several different people. You don't do work right inside the remote repository so there's no Working Tree (the files in your project that you edit), just bare repository data.



