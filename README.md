# dotfiles

## iTerm

path to config directory needs to be set in iTerm settings.

## Fish

``ln -s .dotfiles/fish/ .config/fish``

```
fish
fish_add_path /opt/homebrew/bin
echo "/opt/homebrew/bin/fish" | sudo tee -a /etc/shells
chsh -s /opt/homebrew/bin/fish
```

## Nano

Nano comes from https://github.com/sheharyarn/dotfiles/blob/master/Nano/README.md

```
rm ~/.nanorc    # delete it if it's already there
ln -s ~/.dotfiles/Nano/nanorc.symlink ~/.nanorc
```
