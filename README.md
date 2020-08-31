# zsh

My ZSH Config

## Setup

```
touch "$HOME/.cache/zshhistory"
#-- Setup Alias in $HOME/zsh/aliasrc
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >> ~/.zshrc
```

## Get Dependencies

- zsh-syntax-highlighting - syntax highlighting for ZSH in standard repos
- autojump - jump to directories with j or jc for child or jo to open in file manager
- zsh-autosuggestions - Suggestions based on your history

### Debian Dependencies

```bash
sudo apt install zsh-syntax-highlighting autojump zsh-autosuggestions
```

### Arch Dependencies

```bash
yay -S zsh-syntax-highlighting autojump zsh-autosuggestions
```
  
Finish the conversion by changing your user in /etc/passwd to /bin/zsh instead of /bin/bash

or typing `chsh $USER` and entering `/bin/zsh`
