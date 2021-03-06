# Terminal Toolbelt

This repository consists of my personal bash aliases and functions.

## Installation

##### Clone this repo
```bash
git clone https://github.com/vighiosif/terminal-toolbelt.git
```

##### Set the current directory path

```bash
cd terminal-toolbelt/
cp loader.sh_TEMPLATE loader.sh
nano loader.sh
```

##### Open your rc file (may differ)

```bash
nano ~/.bashrc
 - OR -
nano ~/.zshrc
```

##### Add these lines:

```bash
source {{full-path-to-this-repo}}/loader-{os-that-you-are-using}.sh
```

Comment out the plugins code as it's overwriten in the sources/config.sh file

## Optional

##### Install oh-my-zsh
https://github.com/robbyrussell/oh-my-zsh
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

##### Install zsh-syntax-highlighting
https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md
```bash
brew install zsh-syntax-highlighting
```

##### Install zsh-autosuggestions
https://github.com/zsh-users/zsh-autosuggestions
This repo automatically sources the files from the default install location
```bash
git clone git://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions
```

##### Install Powerline Fonts
https://github.com/powerline/fonts
```bash
git clone https://github.com/powerline/fonts.git && cd fonts && ./install.sh
cd .. && rm -rf fonts
```
Try with
```bash
echo "\ue0b0 \u00b1 \ue0a0 \u27a6 \u2718 \u26a1 \u2699"
```

##### Install Agnoster Theme for oh-my-zsh
https://github.com/agnoster/agnoster-zsh-theme
just replace the default theme "robbyrussel" with "agnoster"
```bash
nano ~/.zshrc
```

##### Install Solarized theme for OSX Terminal app

Use the default one
https://github.com/tomislav/osx-terminal.app-colors-solarized

Or use the ones located in this repo at /osx-terminal-theme.
These are tweaked a bit to be used with agnoster, autosugestions and syntax-highlighting

Double click on theme. Go to prefferences and click "default" once you make sure the theme is selected.
