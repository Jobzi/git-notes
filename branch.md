# BRANCH

````bash
git branch #show current branch
````
````bash
git branch -a #show all branches
````
````bash
git branch new_branch #create new branch
````
-d
--delete
Delete a branch. The branch must be fully merged in its upstream branch, or in HEAD if no upstream was set with --track or --set-upstream-to.

-D
Shortcut for --delete --force.
````bash
git branch -d new_branch #delete branch
````
````bash
git branch -M new_branch #rename branch
````
