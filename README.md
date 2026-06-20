# terminal-ghostty-ohmyposh

Setup Ghostty terminal with Oh My Posh, JetBrains Mono Nerd Font, FZF, and zsh syntax highlighting.

## 1. Install Ghostty

Download and install Ghostty from:

[Ghostty Download](https://ghostty.org/download)

## 2. Install Oh My Posh

```shell
brew install oh-my-posh
```

Check version:

```shell
oh-my-posh --version
```

Open `.zshrc`:

```shell
vim ~/.zshrc
```

Add one Oh My Posh theme to `~/.zshrc`:

```text
eval "$(oh-my-posh init zsh --config ~/.cache/oh-my-posh/themes/agnoster.omp.json)"
```

or

```text
eval "$(oh-my-posh init zsh --config ~/.cache/oh-my-posh/themes/aliens.omp.json)"
```

or

```text
eval "$(oh-my-posh init zsh --config 'https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/main/themes/M365Princess.omp.json')"
```

Reload shell:

```shell
source ~/.zshrc
```

## 3. Install Font

```text
brew install font-jetbrains-mono-nerd-font
```

## 4. Configure Ghostty

Create config folder:

```shell
mkdir -p ~/.config/ghostty
```

Open Ghostty config:

```shell
vim ~/.config/ghostty/config
```

Add config:

```text
font-family = "JetBrainsMono Nerd Font"
font-size = 14
theme = Dracula
window-padding-x = 10
window-padding-y = 10
```

Restart Ghostty or reload the config.

## 5. Install FZF

```shell
brew install fzf
$(brew --prefix)/opt/fzf/install
```

## 6. Install zsh-syntax-highlighting

```shell
brew install zsh-syntax-highlighting
```

Open `.zshrc`:

```shell
vim ~/.zshrc
```

Add this line to `~/.zshrc`:

```shell
source $(brew --prefix)/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```

Reload shell:

```shell
source ~/.zshrc
```
