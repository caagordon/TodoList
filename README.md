# TodoList
ToDo List Exercise for Danny. Write a to do list app that supports all 4 "CRUD" operations for 3 different entities. Feel free to use whatever you want as parameters and write as many private utility functions, variables, and classes as you want but no new global variables and only those 5 functions, the 3 entities, and the main method are allowed to be public. Everything else you have creative freedom.

## To get Started With git

* Open the unix terminal on your computer (defaults to off on PCs so you might need to check your settings) and navigate to where you want the project to be. 

* git clone will download the project for you so you will only ever have to do this once. You can find that link at the upper right too.
```
git clone https://github.com/caagordon/TodoList.git
```

* git checkout will change branches and adding -b creates a new one. You want to work on a different branch to keep yourself organized and make it so someone else can review your work easily. And `branchName` can be anything. Like for example "iteration-1" or "dannysBranch" or "newBranch" whatever it is doesn’t really matter as long as it’s not `master`.
```
git checkout -b branchName
```

* When you want to essentially be saving your work on git, which is just a generally good idea because you can always go back.
git add will add the files to be "saved" or commited so you don’t need to commit every file. git commit will commit it or essentially save it locally on your machine. The message can be anything too.
```
git add filename.py
git commit -m "message"
```

* When you want to send it up here to this website so that I or anyone else can see it you will push it. `origin` means right here on this github site as opposed to your local machine and adding your branch name will push to your branch and create one if its not already there.
```
git push origin branchName
```

* If you want to download something that I or anyone else has put here you're going to pull it. I imagine you will almost only ever pull from the master branch but you can replace master with another branch name

```
git pull origin master
```

* A command you will use most often is `git status` it will show you where you are the process. It will show you what files you have changed and if they've been added or committed yet.


* The git documentation is pretty good and this is also one of my favorite sites.
https://git-scm.com/docs
https://ohshitgit.com/


