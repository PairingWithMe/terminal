# terminal

## Install

### [Oh My Zsh](https://ohmyz.sh/#install)

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### [gruvbox](https://github.com/herrbischoff/iterm2-gruvbox/tree/master)

Import to iTerm2 colors.

```
(cd ~/Downloads && curl -O https://github.com/herrbischoff/iterm2-gruvbox/raw/master/gruvbox.itermcolors)
```

### [powerlevel10k](https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#installation)

```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

Set `ZSH_THEME="powerlevel10k/powerlevel10k"` in ~/.zshrc.

```
source ~/.zshrc
```
### [autocomplete](https://github.com/zsh-users/zsh-autosuggestions)

```
brew install zsh-autosuggestions
source $(brew --prefix)/share/zsh-autosuggestions/zsh-autosuggestions.zsh
```

### [highlight](https://github.com/zsh-users/zsh-syntax-highlighting?tab=readme-ov-file)

```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

## Plugins

```
vi ~/.zshrc

plugins=(git golang node npm docker docker-compose zsh-syntax-highlighting)
```
