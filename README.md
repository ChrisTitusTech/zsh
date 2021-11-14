# ZSH
My ZSH config

## Setup
  - Clone the repository to your home folder
```
git clone --recursive https://github.com/jiriks74/zsh
```
### `powerlevel10k` theme
  - Link the `zsh` file to your home folder as `.zshrc`
```
ln -s ~/zsh/zshrc ~/.zshrc
```
  - Set the `powerlevel10k` theme the way you like it
```
zsh
```
  - If configuration won't start automatically, just run
```
p10k config
```
### `pure` shell theme
  - Link the `zsh.pure` file to your home folder as `.zshrc`
```
ln -s ~/zsh/zshrc.pure ~/.zsh
```  

## Get Dependancies

### Included in this repository
  - `zsh-syntax-highlighting` - syntax highlighting for ZSH
  - `zsh-autosuggestions` - Suggestions based on your history
  - `powerlevel10k` theme - The the actual theme
  - `pure` - Pure shell look for zsh

### Get this from your distribution's repository
  ### Debian Dependencies
    ```bash
    sudo apt install autojump zsh
    ```

  ### Arch Dependencies
    ```bash
    yay -S autojump zsh
    ```

### Recomended for `powerlevel10k`
  - [`nerd-fonts`](https://github.com/ryanoasis/nerd-fonts "nerd-fonts github page") - I recomend `MesloLGS NF Regular`

## Set as default
To set zsh as default shell for your user, edit `/etc/passwd` (from `/bin/bash` to `/bin/zsh`)

### There are two ways:
#### Running this command:
```chsch $USER```

#### Modifying `/etc/passwd`
  * Change your user in /etc/passwd to /bin/zsh instead of /bin/bash
<details>

  * Find line containing your username
  * Put your username instead of `user`

From: `user:x:1000:1000::/home/user:/bin/bash`

To:   `user:x:1000:1000::/home/user:/bin/zsh`
</details>

## What I used
My config is based on Chris Titus's config, `powerlevel10k` theme and `pure`
