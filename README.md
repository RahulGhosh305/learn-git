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

- git commit --amend --no-edit (Set commit without no messeges it set previous commit message)

- git branch -M “rename_branch” (Rename branch name)

- git remote add origin “remote_repository_url” (Add github remote repository)

- git remote -v (Show remote repository url)

- git push -u origin main | git push (Push code to remote repository)

- git push --set-upstream origin main --force

- git status | git status -s

- git log | git log --oneline

- git log --oneline --graph --all | git log --all

- git clone “remote_repository_url”

- git clone “remote_repository_url” folder_name

- git fetch

- git fetch “remote_repository_url”

- git pull origin main

- git branch | git branch -r | git branch --all (Show git branches)

- git branch branch_name

- git checkout branch_name

- git checkout -b branch_name

- git branch -d “branch_name” | git branch -D “branch_name”

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
