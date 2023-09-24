Git commands for new users:

1. **Initialize a New Git Repository**: Start tracking changes in a new or existing project.
   ```
   git init
   ```

2. **Clone a Repository**: Create a copy of a remote repository on your local machine.
   ```
   git clone <repository_url>
   ```

3. **Check the Status**: View the status of your current repository, showing changes that need to be committed.
   ```
   git status
   ```

4. **Add Changes**: Stage changes for commit.
   ```
   git add <file_name>      # Stage a specific file
   git add .               # Stage all changes
   ```

5. **Configure Git**: Set your name and email for Git commits.
    ```
    git config --global user.name "Your Name"
    git config --global user.email "youremail@example.com"
    ```

6. **Commit Changes**: Create a snapshot of the staged changes.
   ```
   git commit -m "Your commit message"
   ```

7. **View Commit History**: See a list of all commits in the current branch.
   ```
   git log
   ```

8. **Create a New Branch**: Start a new branch to work on a feature or bug fix.
   ```
   git branch <branch_name>
   ```

9. **Switch Branches**: Move between branches.
   ```
   git checkout <branch_name>
   ```

10. **Merge Branches**: Combine changes from one branch into another.
   ```
   git merge <branch_name>
   ```

11. **Pull from Remote**: Fetch changes from a remote repository and merge them into your current branch.
    ```
    git pull origin <branch_name>
    ```

12. **Push to Remote**: Upload your local changes to a remote repository.
    ```
    git push origin <branch_name>
    ```

13. **Discard Changes**: Remove local changes and revert to the last committed state.
    ```
    git reset --hard HEAD
    ```

14. **Undo the Last Commit**: Remove the last commit but keep changes staged.
    ```
    git reset --soft HEAD~1
    ```

15. **Check Remote Repositories**: List remote repositories associated with your project.
    ```
    git remote -v
    ```


These are some of the most commonly used Git commands. Remember to replace `<repository_url>` and `<branch_name>` with the actual repository URL and branch names you are working with. Git has many more commands and options, so it's a good idea to refer to the official documentation or use `git --help` for more information on each command.
