#CREATE REPOSITORIES

git init [project_name] 	Creates a new repo
git clone [url]			Downloads a project and its entire history

##MAKE CHANGES TO THE REPOS

git status
git diff
git add [file]
git diff --staged
git reset [file]
git commit -m "[descriptive message]"

##GROUP CHANGES

git branch
git branch [branch-name]
git checkout [branch-name]
git merge [branch]
git branch -d [branch-name]

##REVIEW HISTORY

git log
git log --follow [file]
git diff [first-branch]...[second-branch]
git show [commit]

##REDO COMMITS

git reset [commit]
git reset --hard [commit]

##SYNCHRONIZE CHANGES

git fetch [bookmark]
git merge [bookmark]/[branch]
git push [alias] [branch]
git pull


