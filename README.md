# skillshop_git_042925
CAPP Skillshop to learn how to use git and github as part of a team.

### Step 1: Clone the repository
```bash
cd path/to/your/directory
git clone git@github.com:[]/skillshop_git_042925.git
```

### Step 2: Create a new branch
```bash
git pull
git switch -c <your-branch-name>
```

### Step 3: Make changes
```bash
# Edit the files you want to change
```
### Step 4: Stage the changes
```bash
# check the status of your changes
git status
git add <file1> <file2> ...
# or to stage all modified files
# git add -u 
# git add .
```
### Step 5: Commit the changes
```bash
git commit -m "Your commit message"
# commiting adds the staged changes to the git repository. You have officially
# taken a snapshot of your repository as of this commit.
```
### Step 6: Push the changes to your branch
```bash
git push origin <your-branch-name>
# or also can just use  
# git push
# In plain english, this reads as, "Send the changes in my current branch to the remote repository named 'origin' under the branch called <your-branch-name>"
```

### Step 7: Create a pull request
1. Go to the GitHub repository.
2. Click on the "Pull requests" tab.
3. Click on the "New pull request" button.
4. Select your branch from the "compare" dropdown.
5. Click on the "Create pull request" button.
6. Add a title and description for your pull request.
7. Click on the "Create pull request" button again to submit it.

### Step 8: Review and merge the pull request
1. Go to the "Pull requests" tab in the GitHub repository.
2. Click on your pull request.
3. Review the changes and comments.
4. If everything looks good, click on the "Merge pull request" button.
5. Confirm the merge.
6. Delete your branch if you no longer need it.

### Step 9: Pull the changes to your local repository
```bash
git switch main
git pull
```

## Optional Steps
# Step 10: Delete your branch locally
```bash
git branch -d <your-branch-name>
```
# Step 11: Clean up remote branches
```bash
git fetch --prune
```
# Step 12: Update your local repository
```bash
git pull
```
# Step 13: Check the status of your local repository
```bash