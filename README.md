# git-commands
Git important command that helps us to complete our task


# Git:: show files only on commit id

git diff-tree --no-commit-id --name-only -r <commit-hash>

Or

git show --pretty="" --name-only <commit-hash>
  
# Resolve conflict when checkout from up-stream branch
Step 1: Checkout the target branch and merge in the changes from the source branch. Resolve conflicts.
  git checkout <target-branch(your working branch)>
  git pull <upstream-branch-url> <upstram-branch-name>
Step 2: After the merge conflicts are resolved, stage the changes accordingly, commit the changes and push.
  git commit
  git push <upstream-branch-url> HEAD
Step 3: The pull request will be updated and marked as merged.

# Delete comment push to origin branch
https://ncona.com/2011/07/how-to-delete-a-commit-in-git-local-and-remote/
