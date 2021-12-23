**Scenario**
* First send to github
  * git init
  * git add -A
  * git commit -m "first commit"
  * git remote add origin <repourl>
  * git push -u origin master

* Send branch to github
  * git checkout -b <branchname>
  * git add -A
  * git commit -m "first branch"
  * git remote add origin <repourl>
  * git push -u origin <branch name

                               
**Command**
* Branch
  * List of branch : git branch
  * Generate new branch(in local) : git branch <branchname>
  * Delete brach : git branch -d <branchname>
  * Generate new branch & move : git checkout -b <branchname>
  * Back master branch : git checkout master
  * Send branch to remote server : git push origin <branchname>
  * Pull branch from remote server : git pull origin <branchname>
 
* Clone
  * Clone code : git clone <cloneurl>
  * Clone branch : git clone -b <branchname> <cloneurl>

* Status
  * check file status : git status

* Pull
* Remote
* Merge
* Tag
* Fetch

  
