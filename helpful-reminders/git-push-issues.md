- start off by just trying 'git push origin'

- try ben's handy trick: git config --global --add --bool push.autoSetupRemote true

if that doesn't work:
- check typecase of the remote & local branches

if there's a difference in the typecase or the spelling isn't exact:
- git push
- git will prompt you to do a 'git push origin set-upstream....' -- copy that language but make sure the upstream branch is spelled exactly the way it needs to be (should be the exact same spelling of the remote branch so that you push your branch to the existing branch)
- after this, you should have properly set up the upstream and you can push your code as normal