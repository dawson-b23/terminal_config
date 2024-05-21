# Prerequisites

# Update your software repositories.
sudo apt-get update
sudo apt-get upgrade

# Install Git.
sudo apt-get install -y git

# Install Vim.
sudo apt-get install -y vim
```

# Installation

### Powerline (and fonts)
```bash
./install_powerline.sh
```

### ZSH, OhMyZSH and Plugins
```bash
./install_terminal.sh
```
### Profile (plugins, theme, font and color)
```bash
# You don't need to execute this - it's part of the script already.
(cd ~/.oh-my-zsh/custom/plugins && git clone https://github.com/zsh-users/zsh-syntax-highlighting)
(cd ~/.oh-my-zsh/custom/plugins && git clone https://github.com/zsh-users/zsh-autosuggestions)
```
```bash
./install_profile.sh
```
