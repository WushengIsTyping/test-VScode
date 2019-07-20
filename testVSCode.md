# test vscode

This file is used to test if I can push updates to my repository on github using vscode.

I'm not sure which branch will this file be push to.

This is pushed to newBranch. Even though it has a warning of "no up-stream branch".

# Associateing remote and local branch

If you have more than one branch in your repository (on GitHub), when you want to push your commits to your repository, it doesn't know which branch to push to.
So you have to associate remote and local branch.
> git push --set-upstream \[remote] \[branch name]

<p> And remember you are associating the local branch you're current in with that \[branch name].