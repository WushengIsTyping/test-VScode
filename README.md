# README

This is a test. To commit file using git bash to github. I will use README editting as example.


### To add or upload new version of file to GitHub

> git add README.md \
> git commit -m "commit information" \
> \# -m for "message"
> git push -u origin master
> \# origin is name for \[remote], master is name of \[branch]

### Add to new branch
Check out your branches
> git branch \# local branches \
> git branch -r \# remote branches, with name of remote repository "origin" \
> git branch -a \# all branches \

If you want to push commit to a non-master branch, you can first move to another branch.
> git checkout \[branch name] 

Then do the add, commit, push things.
