gitdemo

git --version   //Check git version installed

git init    //Initialize Local Repository

git status  //Check Status of Working Tree

git add "FileName"  //Add File to Repository

git add .   //Add all Files to Repository

git commit -m "first commit"    //Commit Change to Index

git commit -a -m "second commit"    //Add all files and Commit

git remote add origin URL   //Add Remote

git remote -v   //Check Remote

git push origin //origin standing for remote server

git push    //Push To Remote Repository short form

git pull origin //origin standing for remote server

git pull    //Pull Latest from Remote Repository short form

git clone URL   //Clone Latest from Remote Repository

git log     //view history and use hash id to revert the previous code

q   //Exit git log

git checkout    

git config --global --list  //Show global configuration

git config --list   //Show configuration of current repository

git config --global user.name "username"

git config --global user.email "email"

git clean -dfx  //remove untracked listed in .gitignore file

git branch  //List all branches

git branch [branch-name]  //Create branch

git checkout [branch-name]  //Switch branch

git checkout -b [branch-name]   //Create and Switch branch

git branch -d [branch-name]     //Delete branch



https://github.com/github/gitignore