**git**

*scenario*

* first send to github
  * git init
  * git add -A
  * git commit -m "first commit"
  * git remote add origin <repourl>
  * git push -u origin master

* send branch to github
  * git checkout -b <branchname>
  * git add -A
  * git commit -m "first branch"
  * git remote add origin <repourl>
  * git push -u origin <branch name

*command*

* branch
  * list of branch : git branch
  * generate new branch(in local) : git branch <branchname>
  * delete brach : git branch -d <branchname>
  * generate new branch & move : git checkout -b <branchname>
  * back master branch : git checkout master
  * send branch to remote server : git push origin <branchname>
  * pull branch from remote server : git pull origin <branchname>
 
* clone
  * clone & download sourcecode : git clone <cloneurl>
  * clone localrepo : git clone /local/repo/path
  * clone remoteserverrepo
 
  
