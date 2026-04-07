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
