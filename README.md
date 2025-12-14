## Git Commands 
### 1. git config
- Set Git username and email (one-time setup).

git config --global user.name "Your Name"
git config --global user.email "email@gmail.com"

### 2. git config --list
- Shows all Git configuration details.

git config --list

### 3. git init
- Initialize a new Git repository.

git init

### 4. git clone
- Copy a GitHub repository to local system.

git clone <repo-url>

### 5. git status
- Shows file status (new / modified / staged).

git status

### 6. git add
- Add files to staging area.


git add file.txt
git add .


### 7. git reset
- Remove files from staging area.


git reset file.txt

### 8. git commit
- Save staged changes.

git commit -m "message"

### 9. git commit -a
- Add + commit tracked files.

git commit -a -m "message"

### 10. git amend
- Modify last commit.

git commit --amend

### 11. git branch
- List all branches.

git branch

### 12. git branch <name>
-Create new branch.

git branch feature1

### 13. git checkout
- Switch branch.

git checkout feature1

### 14. git checkout -b 
- Create + switch branch.

git checkout -b feature1

### 15. git branch -d
- Delete branch.

git branch -d feature1

### 16. git merge
- Merge branches.

git merge feature1

### 17. git rebase
- Reapply commits on top of another base.

git rebase main

### 18. git remote
- Show remote connections.

git remote -v

### 19. git remote add
- Connect local repo to GitHub.

git remote add origin <url>

### 20. git push
- Upload commits to GitHub.

git push
git push -u origin main

### 21. git pull
- Download latest changes.

git pull

### 22. git fetch
- Download changes without merge.

git fetch

### 23. git log
- View commit history.

git log
git log --oneline

### 24. git show
-Show details of a commit.

git show <commit-id>

### 25. git restore
- Undo file changes.

git restore file.txt
git restore --staged file.txt

### 26. git checkout -- 
- Discard file changes.

git checkout -- file.txt

### 27. git clean
- Remove untracked files.


git clean -f
git clean -fd


### 28. git rm
- Delete file from Git.

git rm file.txt

### 29. git mv
- Rename or move file.

git mv old.txt new.txt

### 30. git tag
- Create version tags.

git tag v1.0
git tag

### 31. git stash
- Temporarily save changes.

git stash

### 32. git stash apply 
- Reapply stashed changes.
git stash apply

### 33. git cherry-pick
- Apply a specific commit from another branch.

git cherry-pick <commit-id>

### 34.  git revert
- Undo a commit safely .

git revert <commit-id>

### 35. git reset --soft
-Undo commit, keep changes staged.

git reset --soft HEAD~1

### 36. git reset --mixed 
- Undo commit, keep changes unstaged.

git reset HEAD~1

### 37. git reset --hard
- Remove commit + changes permanently.

git reset --hard HEAD~1

### 38. git blame
- Shows who changed each line.

git blame file.txt

### 39. git grep
- Search text inside repo.

git grep "login"

### 40. git submodule add
- Add another repo inside your repo.

git submodule add <repo-url>

### 41. git submodule update
- Update submodule code.

git submodule update --init --recursive

### 42. git archive
- Create zip/tar of project.

git archive --format=zip HEAD > project.zip

### 43. git verify-commit
- Verify signed commit.

git verify-commit <commit-id>

### 44. git fsck
- Check repository integrity.

git fsck

### 45. git reflog
- Shows all HEAD movements.

git reflog





