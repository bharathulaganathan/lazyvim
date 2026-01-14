# 💤 LazyVim modified by Bharath

For a starter [LazyVim](https://github.com/LazyVim/LazyVim) template, refer to the [documentation](https://lazyvim.github.io/installation).

## Installation

### 🐧 Linux

```sh
# backup current config
mv ~/.config/nvim{,.bak}
mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}

# get new config
git clone https://github.com/bharathulaganathan/lazyvim ~/.config/nvim
```

### 🪁 Windows

```ps
# backup current config
Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak
Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak

# get new config
git clone https://github.com/bharathulaganathan/lazyvim $env:LOCALAPPDATA\nvim
```
