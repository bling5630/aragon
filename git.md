
Git: How to make a single commit of multiple commits when merging pull request?

git checkout master
git merge pull-request-branch --squash
git commit -m "Pull request merged in master"
git push origin master
