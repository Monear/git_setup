# Initializing a Git Repository and Pushing to GitHub over SSH

## Step 1: Initialize a Git Repository

Open your terminal and navigate to your project directory. Then, run the following command to initialize a new git repository:

```bash
git init
```

## Step 2: Add Files to the Repository

Add the files you want to include in your initial commit:

```bash
git add .
```

## Step 3: Commit the Files

Commit the added files with a descriptive message:

```bash
git commit -m "Initial commit"
```

## Step 4: Add the Remote Repository

Add your remote GitHub repository using SSH. Replace `git@github.com:username/repo.git` with your actual repository URL:

```bash
git remote add origin git@github.com:username/repo.git
```

## Step 5: Push to the Remote Repository

Push your changes to the remote repository:

```bash
git push -u origin master
```

If you encounter the following error:

```
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master
```

Run the suggested command to set the upstream branch:

```bash
git push --set-upstream origin master
```

## Summary

1. `git init` - Initializes a new git repository.
2. `git add .` - Adds all files to the staging area.
3. `git commit -m "Initial commit"` - Commits the files with a message.
4. `git remote add origin git@github.com:username/repo.git` - Adds the remote repository.
5. `git push -u origin master` - Pushes the changes to the remote repository.