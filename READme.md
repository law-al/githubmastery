check git version: git --version

config git: git config --global user.name "Lawal"

create a repo: git init

get status: git status

add a file to track:git add filename.extension (add and commit)

add a file to track:git add ./ (add multiple files)

commit: git commit -m "File title" (git commit -m "Add readme.md file")

list of all git commited: git log

restoring to a previous version: git checkout hash(from git log)

head back to the current state: git checkout main

change git from master to main: git branch -M main

Local repo (the repo from your machine when you use git init)
remote repo (the repo pushed to cloud services like github ).

In a team. Each dev have a local repo each and a shared remote repo
link local repo to origin(remote) repo: git remote add origin https://github.com/law-al/githubmastery.git
push code: git push -u origin main

branching: creating a copy of a file (so changes can be made to the copied file)

merging: merging the copied file back to the original file

creating a branch: git branch branch-name

switch to branch: git checkout branch-name

create and switch to branch: git checkout -b branch-name

(will this work ?????)
