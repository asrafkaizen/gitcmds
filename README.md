git commit -am "write comments of edited coding here"
git push -f <remote> <branch> //not tested. to push to a remote
git checkout <branch> //checkout to the new branch
git branch <newBranch> //create a new branch
git branch -d <branch> //delete a local branch
git push origin --delete <branch> //delete a remote branch
ctrl +ins //copy
shift +ins //paste

//pushing a dir
cd <dir>
git init
git add.
git commit -m "messages"
git remote add origin <url>
git remote -v
git push origin master

//reset to previous commit
git log //show all previous commit
git reset --hard <hash of commit>
git push origin master //push it back again

//urls
git clone <url>
git pull <url> //directly merge the pulled code with the current code
git remote set-url origin <url> //change url
git remote rename origin newurl <url>
git remote add origin <url>
