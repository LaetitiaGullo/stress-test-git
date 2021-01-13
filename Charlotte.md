1. Create & clone
   1. Create new repo : git init
   2. clone local repo : git clone /path/to/repo
   3. clone remote repo : git clone ssh
2. Add & remove
   1. add changes : git add "filename"
   2. add all changes : git add .
   3. remove/delete : git rm "filename"
3. Commit & synchronize
   1. commit changes : git commit -m "comment"
   2. push changes to remote repo : git push origin master
   3. update local repo with remote changes : git pull
4. Branches
   1. create new branch : git checkout -b "branch"
   2. switch to master branch : git checkout master
   3. delete branch : git branch -d "branch"
   4. push branch to remote repo : git push origin "branch"
5. Merge
   1. merge changes from another branch : git merge "branch"