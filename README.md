# Useful Git Commands

- git --verison | git -v (Check git version)

- git config --global user.name “user_name” (Set global project username)

- git config --global user.name (Show global username)

- git config --local user.name "user_name" (Set local project username)

- git config --local user.name (Show local username)

- git config --global user.email "user_email" (Set global project user email)

- git config --global user.email (Show global user email)

- git config --local user.email "user_email" (Set local project user email)

- git config --local user.email (Show local email)

- git config --list (Configuration list)

- git init (Git initialize)

- git add file_name | git add . (Add to staged file)

- git restore --staged "file_name" (Back staged file to modified file )

- git rm --cached file_name (Delete form staged file to untract file )

- git commit -m “commit_message_here” (Set message with commit)

- git commit --amend -m “rewrite_typo_fix_commit_message” (Edit with rewrite previous commit message)

- git commit --amend --no-edit (Set commit without no messeges. it set previous commit message)

- git branch -M “rename_branch” (Rename branch name)

- git remote add origin “remote_repository_url” (Add github remote repository)

- git remote -v (Show remote repository url)

- git push -u origin main | git push (Push code to remote repository)

- git push --set-upstream origin main --force (Forcefully push to remote origin)

- git status | git status -s (Check status)

- git log | git log --oneline (Show logs)

- git log --oneline --graph --all | git log --all (Show logs)

- git clone “remote_repository_url” (Clone git repo url)

- git clone “remote_repository_url” folder_name (Clone git repo with rename folder name)

- git fetch (fetch updated code. if use fetch need to be merge code in locally)

- git fetch “remote_repository_url” (Fetch updated code)

- git pull origin main | git pull (Pull latest remote repo code)

- git branch | git branch -r | git branch --all (Show git branches)

- git branch branch_name (Create new branch)

- git checkout branch_name (Switch another branch)

- git checkout -b branch_name (Create new branch and also switch that branch)

- git branch -d “branch_name” | git branch -D “branch_name” (Delete branch)

- git tag tag_name

- git tag -l

- git tag -a tag_name -m "tag_message"

- git push origin tag_name

- git push origin --tags

- git show tag_name

- git show "SHA-Id/Commit object first character"

- git stash

- git stash list

- git stash pop

- git stash pop stash_id

- git reset --hard

- git merge branch_name | git merge origin branch_name

- git merge --no-ff branch_name

- git merge --abort

- git rebase master branch_name

- git rebase --abort

- git diff “commit_id” “commit_id”

- git clean -f | git clean -f -n (delete untract files)
