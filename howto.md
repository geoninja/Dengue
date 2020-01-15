git log
git checkout [sha] # commit with deletion
git revert [sha] # undo commit, files restored
git checkout mybranch4 # will remove files again!
git branch newbranch [hash] # save libs2 in another branch


git reflog
git reset HEAD@{index} #index = commit number when libs was added
git checkout libs5/*
-- copy libs somewhere else temporarily
git status # add and commit new changes if any
-- cannot push changes without pull and deleting libs again
