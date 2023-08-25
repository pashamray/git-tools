# Git tools
This is collection scripts for git

setup
```git clone https://github.com/pashamray/git-tools.git```

### Config

#### user
```git config --global user.name "User Name"```

```git config --global user.email "user@email.com"```

#### init
```git config --global init.defaultBranch main```

### Hooks
global setup ```git config --global core.hooksPath ~/git-tools/hooks```

for one repository setup copy files to your repository `.git/hooks` directory

- **prepare-commit-msg**

  get issue number from branch name and append to commit message

  the branch name must match the pattern `GROUP-1111-username-short-description`

### Ignore files
global setup ```git config --global core.excludesfile ~/git-tools/gitignore```
