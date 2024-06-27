- if you see a merge conflict on your PR, go to VScode and type in git pull --rebase origin main
- it should bring up any conflicts in the left panel under the source control section
- resolve conflicts, refer to main in github on your browser if you need a reference.
- save your changes
- git add . (or specify the files)
- git rebase --continue **Note that this works through each of your commits, so you might see the same things come up again and again while doing this and that is normal 
- This will open the dreaded VIM once conflicts are resolved, to skip adding a commit message just use :wq (write, quit) to get back into your normal terminal
- git push --force-with-lease <branch-name> (this will just skip you creating a commit message)

magic

Also, if you get to a point in the rebase where you are not confident, you can always use git rebase --abort to bring it back to the state it was at the start of these steps.

(thanks, kat!!)