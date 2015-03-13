Git is a distributed version control system .
Git is a free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.
Creating a new branch is quick and simple.
Add merge
Hello world
git remote add origin git@github.com:panlz/learngit.git
git add readme.txt
git commit -m "ddd"
git checkout -b dev.
<<<<<<< HEAD
Creating a new branch is quick and simple.
=======
Creating a new branch is quick & simple.
git log --graph --pretty=oneline --abrev-commit
>>>>>>> feature1
