# terminal-ghostty-ohmyposh
 
### Install Ghostty
[Link Ghostty](https://ghostty.org/download)


### Install Oh My Posh
```shell
brew install oh-my-posh
```

#### Check version
```shell
oh-my-posh --version
```

#### Open zsh
```shell
vim ~/.zshrc
```

#### Add theme to .zshrc file
```text
eval "$(oh-my-posh init zsh --config ~/.cache/oh-my-posh/themes/agnoster.omp.json)"
or
eval "$(oh-my-posh init zsh --config ~/.cache/oh-my-posh/themes/aliens.omp.json)"
or
eval "$(oh-my-posh init zsh --config 'https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/main/themes/M365Princess.omp.json')"
```

#### Reload Or Reopen
```shell
source ~/.zshrc
```

### Install Font
```text
brew install font-jetbrains-mono-nerd-font
```
#### Create folder 
```shell
mkdir -p ~/.config/ghostty
```
#### Open file 
```shell
vim ~/.config/ghostty/config
```
#### Reload Or Reopen
```text
font-family = "JetBrainsMono Nerd Font"
font-size = 14

theme = Dracula

window-padding-x = 10
window-padding-y = 10
```

#### Install FZF 
```shell
brew install fzf
$(brew --prefix)/opt/fzf/install
```

#### Install zsh (zsh-syntax-highlighting) 
```shell
brew install zsh-syntax-highlighting
source $(brew --prefix)/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```
