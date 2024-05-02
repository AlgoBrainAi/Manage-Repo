# Git Commands Cheat Sheet

This README provides a handy reference for commonly used Git commands along with examples and scenarios.

## Getting Started

### git init
Initialize a new Git repository in the current directory.

```bash
git init
```

### git clone [repository URL]
Clone a repository from a remote server to your local machine.

```bash
git clone https://github.com/example/repository.git
```

## Basic Workflow

### git add [file]
Add a file to the staging area.

```bash
git add filename.txt
```

### git commit -m "[commit message]"
Commit the staged changes to the repository with a descriptive message.

```bash
git commit -m "Add new feature"
```

### git status
Display the current status of the repository, including any modified, staged, or untracked files.

```bash
git status
```

## Branching and Merging

### git branch
List all local branches in the repository.

```bash
git branch
```

### git branch [branch name]
Create a new branch with the specified name.

```bash
git branch feature-xyz
```

### git checkout [branch name]
Switch to the specified branch.

```bash
git checkout feature-xyz
```

### git merge [branch name]
Merge the specified branch into the current branch.

```bash
git merge feature-xyz
```

## Collaboration

### git pull
Fetch changes from the remote repository and merge them into the current branch.

```bash
git pull origin main
```

### git push
Push commits from the local repository to the remote repository.

```bash
git push origin feature-xyz
```

### git remote -v
List all remote repositories associated with the local repository.

```bash
git remote -v
```

## Example Scenario

Let's say you want to contribute to an open-source project hosted on GitHub:

1. **Fork the Repository**: Fork the repository to your GitHub account using the GitHub UI.

2. **Clone the Repository**: Clone the forked repository to your local machine.

   ```bash
   git clone https://github.com/yourusername/repository.git
   ```

3. **Create a New Branch**: Create a new branch to work on your feature.

   ```bash
   git checkout -b feature-xyz
   ```

4. **Make Changes**: Make changes to the codebase as required.

5. **Add and Commit Changes**: Add and commit your changes.

   ```bash
   git add .
   git commit -m "Implement feature XYZ"
   ```

6. **Push Changes to GitHub**: Push your changes to your forked repository on GitHub.

   ```bash
   git push origin feature-xyz
   ```

7. **Open a Pull Request**: Open a pull request from your branch to the original repository's main branch using the GitHub UI.

8. **Review and Merge**: Wait for reviews from maintainers and make any necessary changes. Once approved, your changes will be merged into the main branch.

