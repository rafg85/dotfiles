# dotfiles

### .gitconfig tips

- `cp .gitconfig ~`
- `ssh-keygen -t ed25519 -C "email@email.com"`
- `clip < ~/.ssh/id_ed25519.pub`
- `ssh -T git@github.com`
- `vim ~/.ssh/config`
    
    ```
    Host github.com
        Hostname ssh.github.com
        Port 443
        User git
    ```

- `ssh -T git@github.com`
