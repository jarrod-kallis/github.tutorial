1. Go to K:\Projects

2. type: git init GitProject
Should see this:
Initialized empty Git repository in K:/Projects/GitProject/.git/

3. type: git status
         git status -s
Should see this:
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        readme.txt

nothing added to commit but untracked files present (use "git add" to track)

4. type (to add all modified/new files to staging area): git add .

5. type: git status
Should see this:
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   readme.txt

6. type: git commit -m "inital commit"
         git commit -a -m "add all modified/new files and commit"

7. type: git log
         git log --oneline

8. type (if changes made and not added to staging area) : git diff
   type (if changes made and file added to staging area): git diff --cached

9. Add a remote repository (on GitHub.com)
   type: git remote add origin git@github.com:jarrod-kallis/github.tutorial.git
   "git@github.com:jarrod-kallis/github.tutorial.git" comes from GitHub.com

10. Push code to the remote repository
    type: git push origin master
    type in passphrase used when creating SSH key