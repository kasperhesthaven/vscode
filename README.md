# vscode
A simple oh-my-zsh plugin to open VS code a little easier across systems

## Usage

| Command | Description                                      |
|:--------|:-------------------------------------------------|
| _vsc_   | open new Visual Studio Code window               |
| _vsc ._ | open the current directory in Visual Studio Code |

## Installation
Change to oh-my-zsh plugins directory in your terminal:
```sh
cd ~/.oh-my-zsh/custom/plugins
```

Get plugin file:
```sh
wget https://raw.githubusercontent.com/kasperhesthaven/vscode/master/vscode.plugin.zsh
```

Add 'vscode' to your plugins in .zshrc:
```sh
plugins=(
  ... vscode
)
```

Reload .zshrc:
```sh
source ~/.zshrc
```
