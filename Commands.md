# Git Commands
1. Initialize a Git Repository
git init

2. Check Status of Files
git status

3. Stage a Specific File
git add <filename>

Example: git add devops.txt

4. Stage All Files
git add .

5. Unstage a File (Move it from Staged to Untracked)
git rm --cached <filename>

Example: git rm --cached devops.txt

6. Commit Staged Files with a Message
git commit -m "Your commit message"

Example: git commit -m "Adding the devops file"

7. Remove a File from the File System
rm <filename>

Example: rm devops.txt

8. Restore a Deleted File (From Git)
git restore <filename>

Example: git restore devops.txt

9. Configure User Identity (Set Global Username)
git config --global user.name "Your Name"

Example: git config --global user.name "Kunal1117"

10. Configure User Identity (Set Global Email)
git config --global user.email "Your Email"

Example: git config --global user.email "kunaladhangle124@gmail.com"

11. Check Current Branch
git branch

12. Create a New Branch
git checkout -b <branchname>

Example: git checkout -b dev

13. Switch to a Branch
git checkout <branchname>

Example: git checkout master

or

git switch <branchname>

Example: git switch master

14. View Commit History (One Line Per Commit)
git log --oneline

15. Amend the Previous Commit (Reset Author)
git commit --amend --reset-author
