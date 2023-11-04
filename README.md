# ASSIGMENT_DEVOPS
First I created a new repository in github Then i created a new folder in my local system. Inside my folder I opened git bash where I executed these commands

git init

git remote add origin ""https://github.com/duckhitches/ASSIGMENT_DEVOPS.git"

notepad sample.txt (here I added these contents to the file) ESHAN VIJAY SHETTENNAVAR 20211CDV0015

git add .

git commit -m "first commit"

git push origin master

git branch feature-branch

git checkout feature-branch

notepad sample.txt (here I added these contents to the file) 5-cdv-01

git add .

git commit -m "commit on feature-branch"

git push origin feature-branch

git checkout master

git merge feature-branch

git push origin master
