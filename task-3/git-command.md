# Git commands 
 ## After creating new projects 

 ***Note: All content with big brackets [] should be replace.***
 
  1. Git initialization 
        ```
     git init 
        ```

  2. Adding files and folders to git for tracking.
        ```
       Note: for specific files  
       git add [file_name]
       eg: git add index.html 
        ```
        ```
        --> To add all files and folders:   
       git add .
        ```

   3. Git version save or commit 
        ```
        git commit -m [your_commit-message]
        eg: git commit -m "auth feature done"
        ```

4. Change main branch [optional step]  
        ````
        git branch -M [your_new_branch_name]
        ````

5.  Add remote url (link the remote repository url)
    ````
    git remote add origin [remote_repo_url]
    ````
6.  Push the commited coed to the remote repo
    ```
    At initial (-u: upstream)
    git push -u origin [your_branch_name]
    After first push:  git push
    ```
```markdown
# Extra Commands
7. To check the status of git (vcs)
   ```
   git status
   ```
8. To update the remote repo url
   ```
   git remote set-url origin [your_repo_url]

   To Verify/Display added remote url:
   git remote -v
   ```
9. To config the user.name and user.email:
   ```
   Project Based Config:
   git config user.name [your_github_username]
   git config user.email [your_github_email]

   Global Config:
   git config --global user.name [your_github_username]
   git config --global user.email [your_github_email]

   To Verify/Display Config (Note: enter to view more config and q to exit the opened editor):
   git config --list
   ```

# After Changing on Project
   1. git add .
   2. git commit -m "[your_commit_message]"
   3. git push

# Using Personal Access Token (PAT) on https url:
- https://[PAT]@github.com/[github_username]/[project_name]

- git remote add origin https://fhtyjtgdhtjtjhj@github.com/DipakShrestha-ADS/per-day-practice-secb.git

To Update the remote url:
- git remote set-url origin [ your_github_url_with_pat]
```