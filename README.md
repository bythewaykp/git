git init
> initialize an empty repo at the current local directory

git config --global user.name `username`
> set `username` as global username on the local system

git config --global user.email `email@email.com`
> set `email@email.com` as global email id on the local system

git config --global --list
> check the info you just provided

git add .
> Add all files to the staging area

git diff
> show differenecs

git commit -m "`messsage`"
> make a new commit with the commit message `message`

git commit --amend
> commit all latest files to the last commit

git remote add origin `url`
> set remote url `url` as the origin to push to or pull from

git remote -v
> List the remote connections you have to other repos

git push origin main
> push to the remote named origin and its branch named main

git log
> shows a log of all the commits in history till date

git status
> shows the status of the working tree

git fetch `url`
> get files form remote repo at url `url` into local repo but not working directory

git pull `url`
> get files form remote repo at url `url` into working directory

git checkout `branchname`
> switch to branch named `branchname`

git checkout -b `branchname`
> create a new branch named `branchname` and switch to it

git reset -h `commit/ branch`
> reset your current branch to the particular commit/ branch

git merge `branchname`
> merge the `branchname` branch into your current branch

git cherry-pick `commitname1` `commitname2` ..etc
> Take `commitname1` from somewhere else and add it over current working tree

> Take timeline of `commitname1` `commitname2 from somewhere else and add it over current working tree

git rebase `foo` `bar`
> Prenent the changes happened on a completely different timeline `bar` to be happened on `foo`. The timeline will be linear with `bar` ahead of `foo`
