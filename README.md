# learninggit
this branch is created to explore and learn git

# Reset Remote branch to a previous commit
git reset --hard 'commithash'<br />
git push -f origin 'current branch name'

# Reset Local branch to previous commit
  # Softreset - change head keeping the changes
  git reset --soft HEAD~
  
  # Hardreset - change head delete the changes
  git reset --hard HEAD~1


# Delete local branch
git branch -D branch-name

# Process to Reset Remote Branch to a particular commit
 git log --pick commit hash from log to which you want to reset<br />
 git reset --hard {commithash}<br />
 git push -f origin {branchname}<br />