### tell me Qs
## Tell me how to remove them locally and remotely:
git branch -d branch_name ----> for deleting locally
git branch -D branch_name ----> for deleting remoteley

##Tell me how to checkout another branch without commit changes
if u want to discard changes:
git checkout -- <file>
git checkout branch
if you want to keep changes:
git stash save
git checkout branch
git stash pop

