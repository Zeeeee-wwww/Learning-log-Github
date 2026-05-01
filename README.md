```bash
git log --oneline
```

# Learning-log-Github
My first repository which's about using Github.


### 2026.4.3

Updated my personal profile.
Created first repository for recording Github using.
Learning how to using Markdown code blocks. 

### 2026.4.5

Learned how to submit the project to repository file.

### 2026.4.14

Config Git Bash to Github(Using ssh keygen):

  `ssh-keygen -t ed25519 -C ""
  cat ~/.ssh/id_ed25519.pub`
  
  to serve the problem (kex_exchange_identification: read: Software caused connection abort
                       banner exchange: Connection to 20.205.243.166 port 22: Software caused connection abort):
                       
      echo -e "Host github.com\n  Hostname ssh.github.com\n  Port 443\n  User git" >> ~/.ssh/config  #Force Github connection to use port 443
      mkdir -p ~/.ssh
      ssh -T git@github.com + 3Enter.

### 2026.4.29

getting used to controlling codes on Github through Gitbash

## Git Version Control Workflow
1. Navigate to the project directory

```bash
cd /path
```

2. Check current changes

```bash
git status
```

3. Update .gitignore (if needed)

```bash
echo "__pycache__/" >> .gitignore
```

4. Stage all changes

```bash
git add .
```
5. Commit with a descriptive message

```bash
git commit -m "feat: add multimodal real-time voice dialogue, fix WebSocket timeout"
```

6. Pull the latest remote changes before pushing

```bash
git pull --rebase origin main
```

7. Push to the remote repository

```bash
git push
```

Setting Up a New Project with Git & GitHub

1. Navigate to your new project folder

```bash
cd /d/YourNewProject
```
2. Initialize a Git repository

```bash
git init
```

3. Create a .gitignore file (optional but recommended)

```bash
echo "venv/" > .gitignore
echo "__pycache__/" >> .gitignore
```
4. Stage all files

```bash
git add .
```
5. Make the first commit

```bash
git commit -m "Initial commit"
```
6. Create a new repository on GitHub

```text
Go to github.com → click "+" → "New repository"

Enter a repository name (e.g., my-new-project)

Do not check "Add a README file" (you already have local files)

Click "Create repository"
```
7. Link your local repo to the remote

```bash
git remote add origin https://github.com/YourUsername/my-new-project.git
```
8. Rename the default branch (if needed)

```bash
git branch -M main
```
9. Push to GitHub

```bash
git push -u origin main
```

```markdown
# Check out the "Commits" if you want to find the historial versions.
```
