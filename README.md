# ZSH
My ZSH config

## Setup
```
git clone --recursive https://github.com/jiriks74/zsh
ln -s -f ~/zsh/.zshrc ~/.zshrc
```

## Get Dependancies
### Should download with config
  - zsh-syntax-highlighting - syntax highlighting for ZSH
  - zsh-autosuggestions - Suggestions based on your history
  - pure - Pure shell look for zsh
### Get this from your distribution's repository
  - autojump - Jump to directories with j or jc for child or jo to open in file manager
  - zsh - the shell itself

## Set as default
To set zsh as default shell for your user, edit `/etc/passwd` (from `/bin/bash` to `/bin/zsh`)

## What I used
My config is based on Chris Titus's config and pure shell.
