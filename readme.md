### Prerequisites

1. Oh My Zsh 

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

2. Powerlevel10k

```

mkdir -p ~/.local/share/fonts
cd ~/.local/share/fonts
curl -fLO https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Regular.ttf
curl -fLO https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold.ttf
curl -fLO https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Italic.ttf
curl -fLO https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold%20Italic.ttf
fc-cache -f -v

git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

nano ~/.zshrc

ZSH_THEME="powerlevel10k/powerlevel10k"

git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

source ~/.zshrc

p10k configure

```   


## Mac

### CLI Tools 

```
brew install bat bpytop cmatrix exa htop lsd nvm qemu redis zsh-history-substring-search tmux
```

### GUI Tools

```
brew install --cask wireshark raycast rectangle vagrant sublime-text maccy multipass iterm2 insomnia medis alt-tab vlc
```


## Ubuntu / Linux 

`apt install tmux zsh htop glances nvtop nload `


### Other must have macos packages

- Vscode 
- Cascadia Font
- FiraCode
- Shottr
- iterm2 color and themes (https://github.com/mbadolato/iTerm2-Color-Schemes)

Setup 