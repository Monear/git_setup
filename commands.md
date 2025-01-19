## Common Git Commands

### Initialize a Git Repository

```bash
git init
```

- Initializes a new git repository.

### Add all Files to the Staging Area

```bash
git add .
```

- Adds all files to the staging area.

### Commit Changes

```bash
git commit -m "Commit message"
```

> **Note:** `Commit message` should be changed to a relevant message.

- Commits the staged changes with a message.

### Check the Status of the Repository

```bash
git status
```

- Shows the status of the working directory and the staging area.

### View Commit History

```bash
git log
```

- Displays the commit history.

### Clone a Repository

```bash
git clone git@github.com:username/repo.git
```

- Clones a repository into a new directory.

### Remove an Initialized Git Repo

```bash
rm -rf .git
```

- The `-rf` flag is used to remove a folder.
- The `.git` is a hidden directory denoted by the `.` in front of the name.