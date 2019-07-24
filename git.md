# git reference

### creating a repo:

`git init`: starts a new git repo on your local machine (if you used create-react-app, you don't need to do this step)

Make a new repo on Github.com, to copy the URL

`git remote add origin https://github.com/USERNAME/REPO.git` : connect your work to the online git repository 

### pushing to git:

`git add .` : adds all files in the current directory

`git commit -m "message"` : commits the code

`git push origin master`: push to github.com (takes it from local to online)

### pulling from git:

`git clone ... `: clone a repo

`git pull origin master`: pulling new changes from git

`git remote set-url origin url`: after cloning from github, changing the url it is attached to

### notes:

`.gitignore`: this file lets you set which files for git to ignore (create-react-app makes this for you)

`git status`: you can run this to check the status of your commit

