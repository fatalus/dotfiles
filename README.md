# dotfiles

```bash
git clone git@github.com:fatalus/dotfiles.git "$HOME/.config/dotfiles"
```
##### Add files to .*rc file
```bash
# load exports first, then aliases
source "$HOME/.config/dotfiles/prompt.sh"
source "$HOME/.config/dotfiles/exports.sh"
source "$HOME/.config/dotfiles/alias.sh"
source "$HOME/.config/dotfiles/completions/completions.sh"
```

##### Or use the install script
```bash
# for installation only for current user
bash installers/user.sh
# run as root to set everything for root and all users
bash installers/server.sh
```
