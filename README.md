ssh git@github.com:jasnaul1/cloud.git

Create New Repo:

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:jasnaul1/cloud.git
git push -u origin master

Push Existing Repo:

git remote add origin git@github.com:jasnaul1/cloud.git
git push -u origin master

git config --global user.name "Jas
git config --global user.email jas.naul@me.com
git config --global credential.helper cache
git config --global core.editor vim|xemacs|joe
git config --global core.editor vim
git config --global merge.tool vimdiff
git config --global alias.co checkout
git config --global alias.ci commit

mkdir /home/git#
