# git-101
Basic to intermediate git commands

## 1. 𝐑𝐞𝐩𝐨𝐬𝐢𝐭𝐨𝐫𝐲 𝐁𝐚𝐬𝐢𝐜𝐬

Clone a Repository:
```
git clone <repository_url>
```
Initialize a Repository:
```
git init
```

## 2. 𝐖𝐨𝐫𝐤𝐢𝐧𝐠 𝐰𝐢𝐭𝐡 𝐁𝐫𝐚𝐧𝐜𝐡𝐞𝐬

Create a New Branch:

git branch <branch_name>

Switch to a Branch:

git checkout <branch_name>

Create and Switch to a New Branch:

git checkout -b <new_branch_name>

List Branches:

git branch


## 3. 𝐂𝐨𝐦𝐦𝐢𝐭𝐭𝐢𝐧𝐠 𝐂𝐡𝐚𝐧𝐠𝐞𝐬

Stage Changes:

git add <file_name>

Stage All Changes:

git add .

Commit Changes:
 
git commit -m "Commit message"


## 4. 𝐏𝐮𝐥𝐥𝐢𝐧𝐠 𝐚𝐧𝐝 𝐏𝐮𝐬𝐡𝐢𝐧𝐠

Pull Changes from Remote:
 
git pull origin <branch_name>

Push Changes to Remote:
 
git push origin <branch_name>


## 5. 𝐌𝐞𝐫𝐠𝐢𝐧𝐠 𝐂𝐡𝐚𝐧𝐠𝐞𝐬

Merge Branch into Current Branch:
 
git merge <branch_name>


## 6. 𝐖𝐨𝐫𝐤𝐢𝐧𝐠 𝐰𝐢𝐭𝐡 𝐑𝐞𝐦𝐨𝐭𝐞𝐬

Add a Remote Repository:
 
git remote add <remote_name> <repository_url>

List Remote Repositories:
 
git remote -v


## 7. 𝐇𝐚𝐧𝐝𝐥𝐢𝐧𝐠 𝐂𝐨𝐧𝐟𝐥𝐢𝐜𝐭𝐬

Check for Conflicts:
 
git diff

Resolve Conflicts and Continue Merge:

git add <file_name>
git merge --continue


## 8. 𝐆𝐢𝐭𝐇𝐮𝐛 𝐀𝐜𝐭𝐢𝐨𝐧𝐬

Workflow Syntax Checking:

git pull origin <branch_name>
git push origin <branch_name>


## 9. 𝐌𝐢𝐬𝐜𝐞𝐥𝐥𝐚𝐧𝐞𝐨𝐮𝐬

Check Git Status:
 
git status

View Commit History:
 
git log

Ignore Files (Add to `.gitignore`):
 
echo "<file_name>" >> .gitignore
