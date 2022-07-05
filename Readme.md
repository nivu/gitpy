```
git --help
git init
git status
git add filename
git add .
```

.gitignore file


git config user.name "Navaneeth"
git config user.email "navneetnivu07@gmail.com"

## Generating ssh key and adding to account
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

```
ssh-keygen -t ed25519 -C "your_email@example.com"
```

filename, password is empty(default)

```
eval "$(ssh-agent -s)"
```

clip < ~/.ssh/id_ed25519.pub


