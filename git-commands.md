Task 1: Install and Configure Git

how to install git in linux 

apt-get install git (ubuntu)	

use comand 

sudo apt-get  update (this command use for update linux server)
sudo apt-get install git (this for install git )
git --version           (this command use for check git version info)


2. Set up your Git identity — name and email

git config --global user.name "github_name"  
git config --global user.gmail "gmail"

3. Verify your configuration

git config --list ( this command use for verify yourconfiguration )


Task 2: Create Your Git Project

mkdir devops-git-practice (create a new dir)
git init (this command use for initialize this foler/dir and this crete a hidden .git folder)
git status (git status is display the current state of git repo/we are on which branch like master)

.git Git repository ka internal database hai. Isme commits, branches, configuration aur Git ka metadata store hota hai.


Task 3: Create Your Git Commands Reference

basic workflow

git init 
git add .
git status 
git commit -m "add git-command refre"
git log

 Viewing Changes

git diff ( Shows changes in the working directory that have not been staged. )
git diff --staged (Shows changes that are currently staged.)


Task 4: Stage and Commit

Stage your file 
git add filename (  )

Check what's staged - (git diff --staged) this show what is changes in current	 staged 

Commit with a meaningful message  - git commit  -m "Add Git commands"

View your commit history - git log/git log --oneline


