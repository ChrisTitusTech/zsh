# zsh
My ZSH Config

## Setup
```
wget https://github.com/ChrisTitusTech/zsh/raw/master/.zshrc -O ~/.zshrc
mkdir -p "$HOME/.zsh"
wget https://github.com/ChrisTitusTech/zsh/raw/master/.zsh/aliasrc -O ~/.zsh/aliasrc
git clone https://github.com/sindresorhus/pure.git "$HOME/.zsh/pure"
```
## Get Dependancies 
  - zsh-syntax-highlighting - syntax highlighting for ZSH in standard repos
  - autojump - jump to directories with j or jc for child or jo to open in file manager
  - zsh-autosuggestions - Suggestions based on your history
  
Finish the conversion by changing your user in /etc/passwd to /bin/zsh instead of /bin/bash
