# usefull-terminal-commands
# GitHub
git init - creates locally needed git-files for current project

git remote add origin 'link to repo' - publish local project to existing repo

git remote -v - check list of origins

git pull <origin link> <origin branch (master}> - clone repo locally to empty folder (only with git init) from remote repository

git checkout <commit> - go to commit #f3e3bc5-version
  
git rm -r --cached file.ts - untracks file.ts from git system (also needed add file.ts to gitignore

git checkout -b fixes - create and switch to new branch "fixes" locally

git status - 

git add . - 

git commit -m "message" - 

git push origin fixes - pushes "fixes" branch from local computer to origin github

git switch main - switches to branch "main" from current branch

git branch -D fixes - deletes existing branch "fixes" locally

git pull origin main - pulls "main" branch from origin (github) to local computer
 
git checkout <old_name> & git branch -m <new_name> - switch to <old_name> & rename

git branch - list of branches

git branches -r - list of remote branches
  
git branch -a - to see all local and remote branches

# Nextj
nest g module auth - 
nest g controller auth - 
nest g service auth --no-spec - generates service "auth" inside auth.module without test file

npx create-next-app <AppName> --use-npm - create new next-application
npm i -D typescript @types/react @types/node +
npm run dev - generates tsconfig.ts

# Heroku
heroku logs --tail --app my_heroku_app_name
  
# NVM - changes current node-version
usefull source: https://habr.com/ru/company/timeweb/blog/541452/
Run cmd-window as Administrator

nvm ls - list of installed node versions

nvm install lts - installs latest node version

nvm use 12.22.6 - changes current node-version in use to v12.22.6

# PORT
npx kill-port 3000 8080 4200
