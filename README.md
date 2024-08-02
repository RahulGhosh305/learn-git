# Useful Git Commands

- git --verison | git -v

- git config --global user.name “user_name”

- git config --global user.name

- git config --local user.name "user_name"

- git config --local user.name

- git config --global user.email "user_email"

- git config --global user.email

- git config --local user.email "user_email"

- git config --local user.email

- git config --list

- git init

- git add file_name | git add .

- git rm --cached file_name

- git commit -m “commit_message_here”

- git commit --amend -m “rewrite_typo_fix_commit_message”

- git commit --amend --no-edit

- git branch -M “rename_branch”

- git remote add origin “remote_repository_url”

- git remote -v

- git push -u origin main | git push

- git push --set-upstream origin main --force

- git status | git status -s

- git log | git log --oneline

- git log --oneline --graph --all | git log --all

- git clone “remote_repository_url”

- git clone “remote_repository_url” folder_name

- git fetch

- git fetch “remote_repository_url”

- git pull origin main

- git branch | git branch -r | git branch --all

- git branch branch_name

- git checkout branch_name

- git checkout -b branch_name

- git branch -d “branch_name” | git branch -D “branch_name”

- git tag tag_name

- git tag -l

- git tag -a -m "tag_message" tag_name

- git push origin tag_name

- git push origin --tags

- git show tag_name

- git show "SHA-Id/Commit object first character"
