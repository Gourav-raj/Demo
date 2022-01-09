### Hey there this is master

## master is king
   ## change in master 
## features is king
   ## change from features

## 1 if wrong commit message then use git commit --amend -m "Correct msg"
## 2 if commited to wrong branch then use 
        1 git checkout <correct branch>
        2 git cherry-pick <hashofthatcommit> (this will not delete commit from other branch)
        3 to also delete the wrong commit use 
            git reset --soft  ==> keep changes in staging files
                      --hard  ==>remove the changes 
                      default is med --> move to unstage 
## 3 deleting untracked files 
    1 git clean -df

## 4 if want to change the commit but other people might have used previous commit to undo that commit use git revert unlike reset this will change history add and additional commit reverting(undoing) the commit
    1 git revert <hash>