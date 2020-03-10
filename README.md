# Git Tutorial - workout
git init<br />
git status<br />
git log<br />
git log --oneline<br />
cat <filename><br />
touch <filename><br />
vi <filename>    Esc:wq<br />

vi .gitignore $add gitignore<br />

git add . $add all files<br />
git add <filename> $add specific file<br />
git commit -a -m "<msg>" $to commit all files<br />

git checkout <commit id>    $to go purticular commit<br />
git checkout master     $to go recent<br />
git reset --hard <commit id>   $remove post commits<br />

git branch $list all branches<br />
git branch <branch name> $checkout branch<br />
or 
git checkout -b <branch name>  $create branch and checkout<br />

git checkout <master>   $to branch<br />
git merge <develop>   $from branch<br />


GITHUB<br />

git remote add origin <git url .git><br />

git init<br />
git add README.md<br />
git commit -m "first commit"<br />
git remote add origin <remote git url><br />
git push -u origin master<br />
git push -u origin develop<br />

git pull origin master  $pull file from github<br />

git clone <repo Url><br />

git --bare init<br />
A bare Git repository is typically used as a Remote Repository that is sharing a repository among several different people. You don't do work right inside the remote repository so there's no Working Tree (the files in your project that you edit), just bare repository data.



