# ZSH
My ZSH config

## Setup
  - Clone the repository to your home folder
```
git clone --recursive https://github.com/jiriks74/zsh
```
  - Link the zshrc file to your home foled (`powerlevel10k` theme)
`ln -s ~/zsh/zshrc ~/.zshrc`
  - Or link the zshrc file configured for pure
`ln -s ~/zsh/zshrc.pure ~/.zsh`

## Get Dependancies
### Included in this repository
  - zsh-syntax-highlighting - syntax highlighting for ZSH
  - zsh-autosuggestions - Suggestions based on your history
  - pure - Pure shell look for zsh
### Get this from your distribution's repository
  - autojump - Jump to directories with j or jc for child or jo to open in file manager
  - zsh - the shell itself

## Set as default
To set zsh as default shell for your user, edit `/etc/passwd` (from `/bin/bash` to `/bin/zsh`)

### Exampe:
  - Put your username instead of `user`
From: `user:x:1000:1000::/home/user:/bin/bash`
To:   `user:x:1000:1000::/home/user:/bin/zsh`

## What I used
My config is based on Chris Titus's config, `powerlevel10k` theme - old config `pure shell`
