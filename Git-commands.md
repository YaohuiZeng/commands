* `git add -A` = `git add --all`, is equivalent to `git add .`; `git add -u`.
* `git commit -m`
* `git push -f origin HEAD^:master`: undo the push
* add `#L10-20` to URL of code file: highlight lines 10 - 20, for example: https://github.com/YaohuiZeng/Bayesian-changepoint/blob/master/M1_DiscretePrior.R#L10-L20
* clone a git repository into a specific folder: `git clone git@github.com:whatever folder-name`
* [exist from text window in Git](http://stackoverflow.com/questions/9171356/how-do-i-exit-from-the-text-window-in-git): `:q`.

### [Revert commits](http://stackoverflow.com/questions/4114095/how-to-revert-git-repository-to-a-previous-commit)
* `git reset --hard <SHA>`: hard delete any local modifications.
* `git revert <SHA>`: revert a commit.
* `git revert HEAD~2..HEAD`: revert the last two commits.
* `git checkout <SHA>`: go back to a commit, then come back to where you are.
* `git checkout -b old-state <SHA>`: want to make commits, need make a new branch

### reference card: http://www.dataschool.io/git-quick-reference-for-beginners/

### [Resolve merge conflicts](http://stackoverflow.com/questions/161813/how-to-resolve-merge-conflicts-in-git)

