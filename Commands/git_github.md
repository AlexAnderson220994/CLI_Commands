# Git and GitHub Commands

## Creating new repository

- Initialise new git repository
````
git init
````
- Add files
````
git add <filename>
````
OR
````
git add .
````
- Commit files
````
git commit -m "first commit"
````

## Creating a new branch

- Change branch
````
git branch -M main
````

## Push to GitHub

- Change branch
````
git branch -M main
````
- Add remote repository (SSH)
````
git remote add origin git@github.com:AlexAnderson220994/github_repo_name.git
````
- Add remote repository (HTTP)
````
git remote add origin https://github.com/AlexAnderson220994/github_repo_name.git
````
- Push files to GitHub
````
git push -u origin main
````
- Pull files from github
````
git pull -u origin main
````