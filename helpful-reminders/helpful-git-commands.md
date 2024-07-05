## stash

**stashing: git stash
to bring them back: git stash pop**

you can stack git stashes, ie you can git stash 3 different changes -- each git stash pop will bring back most recent -> least recent stash at a time, so you have to git stash pop 3 times in order to un-stash everything.

in order to git stash pop, your current files need to all be saved -- you cannot unstash if there are unsaved changes