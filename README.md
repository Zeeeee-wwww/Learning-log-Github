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

