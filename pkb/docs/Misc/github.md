### Basic Github usage


**Configure Git**

     git config –global user.name “Terry E. Dutcher”
     git config –global user.email “terryinclmich@hotmail.com”

This is only used to track who made what changes. It doesn’t log you in anywhere.

**Repositories**

To create a local repository run **git init**

At any time you can use **git status** to see the current condition of the repository.

To add files to staging area use **git add filename(s)** To add all new and changed files to the staging area use **git add .**

Then commit the changes **git commit -m “Commit Message”**. Commit messages are important in case you need to revert to a previous version of your project.

Clone a repository:

**git clone https://github.com/terryinfcco/terryinfcco.github.io**

Get updates to an existing repository. You'll get messages of what (if anything) has changed.

**git pull origin main** (or current branch)
  
To see a history of commits use **git log**. This will give you author, date and a commit hash for each commit.

To go back to a previous revision do **git checkout hash**. That will create a branch called (HEAD detached at hash). To go back to the master branch do **git checkout master**

To start a new branch do **git branch newbranchname**. At this point both branches match. After you’ve made changes to the new branch, if you like the new stuff from the new branch switch back to the master branch **git checkout master**, then do **git merge newbranchname**.


After Making Changes:
  
    git add .
    git commit -m "Commit message"
    git push origin main   (main might be master in older repos)
    
To get credentials saved on a computer run:

**git config credential.helper store**
  
Then next time you enter your credentials it will store them on your hard disk.    

