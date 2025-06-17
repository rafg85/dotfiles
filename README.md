# dotfiles
My custom config files

### .gitconfig tips

`ssh-keygen -t ed25519 -C "email@email.com"`

`cat ~/.ssh/id_ed25519.pub`

`vim ~/.ssh/config`

```
Host github.com
    Hostname ssh.github.com
    Port 443
    User git
```

`ssh -T git@github.com`