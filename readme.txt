1. Go to K:\Projects

2. type: git init GitProject
Should see this:
Initialized empty Git repository in K:/Projects/GitProject/.git/

3. type: git status
Should see this:
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        readme.txt

nothing added to commit but untracked files present (use "git add" to track)

4. type (to add all untracked files): git add .

5. type: git status
Should see this:
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   readme.txt

6. type: git commit -m "inital commit"

7. git log