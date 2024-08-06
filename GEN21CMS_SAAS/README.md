install GIT link ada di https://git-scm.com/downloads
Windows Credential, use your login into gitlab
netword address: git:https://gitlab.com/
username: johnadam
Password: johnadam123

Git global setup
git config --global user.name "novi tri Nuraini"
git config --global user.email "novinuraini3@gmail.com"

Create a new repository
git clone https://gitlab.com/infotech-qc-support/gen21cms_usermanual.git
cd gen21cms_usermanual
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Push an existing folder
cd existing_folder
git init
git remote add origin https://gitlab.com/infotech-qc-support/gen21cms_usermanual.git
git add .
git commit -m "Initial commit"
git push -u origin master

Push an existing Git repository
cd existing_repo
git remote rename origin old-origin
git remote add origin https://gitlab.com/infotech-qc-support/gen21cms_usermanual.git
git push -u origin --all
git push -u origin --tags
