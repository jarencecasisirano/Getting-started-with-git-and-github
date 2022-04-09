# Getting-Started-with-Git-and-Github

## Cloning a new repository on github

Create a new repository on Github (preferrably with README.md).

On your local machine, open the terminal and navigate to the directory you want to save the cloned directory.

Type "git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY" --> note: link to the repository you want to clone.

The cloned repository on your local machine can sync with the remote repository.

## Uploading local repository on Github

Create a new empty repository on Github.

On your local machine, open the terminal and navigate to the directory you want to upload to Github.

1. echo "# Starting-with-Git-and-Github" >> README.md (create README.md file)
2. git init (initialize Git on the directory)
3. git add README.md (stage changes; alternatively --> "git add ." to add all files)
4. git commit -m "first commit" (commit staged changes with commit message)
5. git branch -M main
6. git remote add origin https://github.com/jarencecasisirano/Starting-with-Git-and-Github.git (connect to remote repository)
7. git push -u origin main (push changes/commits to remote repository)

## Stage changes, commits, and syncing

1. git add file-name; alternatively, use "git add ." to stage changes of all files
2. git commit -m "your-commit-message"
3. git push origin main

To sync changes from remote repository:

1. git pull origin main

### Unstage changes

1. git restore --staged file-name

Note: Remember to add .gitignore!
