# Mylab2

### Basic local Git initialisation and push/pull process as of 05 September 2023.
---
### Steps to create local repo:
1. Create and move into project repo
   ```
   mkdir myProject
   
   cd myProject
   ```
2. Initialise the project folder
   ```
   git init
   ```
3. Go to GitHub and create the repo
4. Find the repo link and enter this command to add local remote repo
   ```
   git remote add origin <repo_link>
   ``` 
5. Update the local repo by pulling latest
   ```
   git pull origin <branch_name>
   ```
6. Create/Modify files as desired
7. Once ready to push, stage the files and add commit message
   ```
   git add <file_names>

   git commit -m "<commit_message>"
   ```
8. Push the changes to GitHub
   ```
   git push origin <branch_name>
   ```
<i>For more commands click [here](https://github.com/joshnh/Git-Commands).</i> 

---
### Miscellaneous commands:
| Command | Description |
| ------- | ----------- |
| `git rm <file_name>`  | removes <file_name> from local repo
| `git rm -rf .git`     | uninitialise the local repo

| Command | Description |
| ------- | ----------- |
| `git branch`                   | shows branches available in local repo
| `git branch -d <branch_name>`  | soft delete a branch
| `git branch -D <branch_name>`  | force delete a branch

| Command | Description |
| ------- | ----------- |
| `git checkout <branch_name>`  | changes working branch to <branch_name>

