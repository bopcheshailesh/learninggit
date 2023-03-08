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
