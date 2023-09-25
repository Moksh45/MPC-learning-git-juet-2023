Git commands for new users:

1. **Initialize a New Git Repository**: Start tracking changes in a new or existing project.

   ```bash
   git init
   ```

2. **Clone a Repository**: Create a copy of a remote repository on your local machine.

   ```bash
   git clone <repository_url>
   ```

3. **Check the Status**: View the status of your current repository, showing changes that need to be committed.

   ```bash
   git status
   ```

4. **Add Changes**: Stage changes for commit.

   ```bash
   git add <file_name>      # Stage a specific file
   git add .               # Stage all changes
   ```

5. **Configure Git**: Set your name and email for Git commits.

   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "youremail@example.com"
   ```

6. **Commit Changes**: Create a snapshot of the staged changes.

   ```bash
   git commit -m "Your commit message"
   ```

7. **Add Remote Repository as "Origin"**: Associate a remote repository with the name "origin" in your local repository.

   ```bash
   git remote add origin <repository_url>
   ```

8. **Push to Remote**: Upload your local changes to a remote repository.

    ```bash
    git push origin <branch_name>
    ```

9. **View Commit History**: See a list of all commits in the current branch.

   ```bash
   git log
   ```

10. **Create a New Branch**: Start a new branch to work on a feature or bug fix.
    ```bash
    git branch <branch_name>
    ```

11. **Switch Branches**: Move between branches.

    ```bash
    git checkout <branch_name>
    ```

12. **Pull from Remote**: Fetch changes from a remote repository and merge them into your current branch.

    ```bash
    git pull origin <branch_name>
    ```

13. **Check Remote Repositories**: List remote repositories associated with your project.
    ```bash
    git remote -v
    ```
