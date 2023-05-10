Hello Learners, Mentiond few git commands which I feell more important and basic and noted down below.
Please fell free to comment on any suggetuins.


## Commands

Setting up git username and email globally in locally
You can use --local insted of --global

```sh
git config --global user.name <"username">
git config --global user.email <"email">
```

Initialise an empty Git Repository

```sh
git init
```

Clone an existing Git Repository 

```sh
git clone <repository URL>
```

Add file/stage to git

```sh
git add <filename>
```

Add all the files to git

```sh
git add .
```

Commit all the staged files to git

```sh
git commit -m "<your commit message>"
```

Restore the file from being modified to Tracked

```sh
git restore <filename>
git checkout <filename>
```

Show the status of your Git respository

```sh
git status
```

Show the branches of your git repository

```sh
git branch
git branch -a
```

Checkout to a new branch

```sh
git checkout -b <branch name>
```

Checkout to an existing branch

```sh
git checkout <branch name>
```

Remove a branch from Git

```sh
git branch -d <branch name>
```

Show remote origin URL

```sh
git remote -v
```

Add remote origin URL

```sh
git remote add origin <your remote git URL>
```

Remove remote origin URL

```sh
git remote remove origin 
```

Fetch all the remote branches

```sh
git fetch
```
Push your local changes to remote branch

```sh
git push origin <branch name>
```

Pull your remote changes to local branch

```sh
git pull origin <branch name>
```

Check you git commits and logs

```sh
git log
git log --oneline
```

Show the diff of what is in branchA that is not in branchB

```sh
git diff branchB...branchA
```

Delete the file from project and stage the removal for commit

```sh
git rm [file]
```

Change an existing file path and stage the move

```sh
git mv [existing-path] [new-path]
```

merge the specified branch’s history into the current one

```sh
git merge [branch]
```

Apply any commits of current branch ahead of specified one

```sh
git rebase [branch]
```

Follow me on Linkedin https://www.linkedin.com/in/eshaprasad-k-u/
