# Common
## Macos CMD
- ls
- ls -all
- rm -r folder/
- cp -r source/ dest/
## Github act
- act -l
- act -j job_name
- act workflow_dispatch -j job_name --input param=value
## Git CMD
- git status
- git config --list
- git config --local user.name "Your Name"
- git config --local user.email "you@example.com"
- git branch
- git branch new_branch
- git checkout branch_name
- git revert commit_id
- git cherry-pick commit-hash
- git cherry-pick <start-commit-hash>^..<end-commit-hash>
- git add folder/
- git add .
- git commit -m "messsge"
- git push <remote> <branch> : git push origin master
- git diff
- git stash
- git stash apply stash@{n}
- git fetch
- git pull
- git pull <remote> <branch>
- git log
- git log --oneline # view commit histories and get commit hash (short commit id)
#### To remove commits in local that they're not push yet.
- git reset --hard <last-pushed-commit-hash>
#### Steps to Cherry-Pick All Unpushed Commits
1. Identify Unpushed Commits:
- git log origin/<branch-name>..HEAD


