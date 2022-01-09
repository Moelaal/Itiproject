#steps to make test branch

git branch test

git checkout test
-create testfile
git add -A
git commit -m "test brach"
/////////////////
git branch dev

git checkout dev
-create devfile
git add -A
git commit -m "dev brach"

///////////////// merge \\\\\\\\\\\
git checkout master

git merge test 
git merge dev



////////// list tags \\\\\\\

git tag --list


////////============\\\\\\\\

delete branch remotly

git push <remote> --delete <branch>

delete branch localy

git branch -d <branch>

///////// delete tags \\\\\\\\\

delete remote tag
git push origin --delete v1.7

delete local tags
git tag -d v1.7


![alt text](https://images.unsplash.com/photo-1641611605871-ae20d4514b74?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80)