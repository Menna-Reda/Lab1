### tell me Qs
## Tell me how to remove them locally and remotely:
git branch -d branch_name ----> for deleting locally
git branch -D branch_name ----> for deleting remoteley

## Tell me how to checkout another branch without commit changes
if u want to discard changes:
git checkout -- <file>
git checkout branch
if you want to keep changes:
git stash save
git checkout branch
git stash pop

## Tell me how to list tags.
git tag

## Tell me how to delete tag locally and remotely.
git tag -d tag_name ------> deletes locally
git tag remote_repo_name :tag_name ---> deletes remotely

![Molly_006-2829x1886-2829x1480-1200x628](https://github.com/user-attachments/assets/106bfd8e-57e2-4378-9607-636a4d29b710)
