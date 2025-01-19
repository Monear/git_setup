# Setting Up a Local Git Environment

This guide will help you set up a local git environment on your machine.

## Step 1: Configure the Default Branch Name

You may see the following hints:

```
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint:   git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint:   git branch -m <name>
```

To set the default branch name to `master`, run the following command:

```bash
git config --global init.defaultBranch master
```

## Step 2: Set Up User Identity

Before making a commit, you need to set up your user identity. Run the following commands to set your email and name:

```bash
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

## Summary

1. `git config --global init.defaultBranch master` - Sets the default branch name to `master`.
2. `git config --global user.email "you@example.com"` - Sets your email for commits.
3. `git config --global user.name "Your Name"` - Sets your name for commits.

Now your local git environment is set up and ready to use.