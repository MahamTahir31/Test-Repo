<h1>Git-Github Concepts Practice</h1>

## Pushing your files to github:

Check git status first
git init
git add <files>
git commit -m "commit message"
git remote -v // This will show you the remote url of your repository. If not shown then run given command
git remote add origin https://github.com/MahamTahir31/Test-Repo.git 
git remote -v // now it will show above url
git push origin main

## To push changes in code:
git add <files>
git commit -m "commit message"
git push -u origin main // now if you do changes in your code so do just following steps every time to push your changes
git add <files>
git commit -m "commit message"
git push
