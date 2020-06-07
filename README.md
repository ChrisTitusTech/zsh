# ZSH
My ZSH config

## Setup
```
git clone --recursive https://github.com/jiriks74/zsh
ln -s -f ~/zsh/.zshrc ~/.zshrc
```

## Get Dependancies
  - zsh-syntax-highlighting - syntax highlighting for ZSH
  - autojump - jump to directories with j or jc for child or jo to open in file manager (ARCH - install via AUR)
  - zsh-autosuggestions - Suggestions based on your history
  - zsh - the shell itself
  - pure - Should download with my setup (Just in case - `git clone https://github.com/sindresorhus/pure.git "$HOME/.zsh/pure"`)

## Set as default
To set zsh as default shell for your user, edit `/etc/passwd` (from `/bin/bash` to `/bin/zsh`)

## What I used
My config is based on Chris Titus's config and pure shell.
