# About
A set of dotfiles created to be used with **stow**. Different categories of configuration files for setting up an Ubuntu.
Includes:
- Fonts
- Background images
- .bashrc aliases
- .zshhrc complete configurations (themes, plugins and more)
- .vscode configs
- Git profile
Mostly used and updated from an Ubuntu. But it should work with most Debian based linux distros.

# Requirements
## Shell
- **ZSH shell**
- **OhMyZsh Framwork**
- **Custom fonts**
- **Powerlevel 10k theme**
- **Curl**
- [**Stow**](https://github.com/malc-j/.dotfiles/tree/main/docs/stow.md)
## Desktop
- **gnome-tweaks**
- **Extension manager**
- **Color Palette**

# Getting started
## Resources
This sections covers the structure of the repository, and the different categories of resources.
### Repository
Start by cloning the repository in your users home directory. If you navigate to the directory of the repository you will see a set of directories.
Each one of theese directories represents a category.
#### Fonts
Here are all the fonts stored. For now I have chosen to only include fonts that other tools and framworks depend on.
Therefore it is very **IMPORTANT** to install these fonts before installing **p10k/powerlevel10k**.
For now just navigate to *./notes* inside of the repository's directory, and install all the fonts by clicking them.
#### Configs
Here are all the different configuration files. These can all be synced att the same time or one by one with **stow**.
#### Backgrounds
Just different background. Nothing more. Nothing Less.
#### Docs 
Additional dokumentation.

## Shell
This covers everything needed to set up the shell.
### Install zsh
`sudo apt-get update`
`sudo apt-get install zsh`
`zsh --version`
### Install curl
`curl --version`
`sudo apt-get install curl`
### Install git
`sudo apt-get install git`
### Install oh-my-zsh framework
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
### Install Fonts
Specific fonts are needed for rendering of icons in the terminal. For everything to work correcly these fonts need to be installed.
However, these fonts can be found inside of the *./fonts* directory inside of this repository. Just click on them and install all **four** of them, then configure your terminal to use **MesloLGS NF**.
### Install Powerlevel 2K
`git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc`
https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#meslo-nerd-font-patched-for-powerlevel10k
Now just restart the terminal and the interactive configuration will start automatically.
If it doesnt, run this command: `p10k configure`

## Desktop
### Palettes
These are some nice pallettes that can be used when customizing the shell.
Each list shows the index position in palette and HEX code the color.
- **Nord**
    0. #2E3440
    1. #2B303C
    2. #3F8062
    3. #4C566A
    4. #D8DEE9
    5. #E5E9F0
    6. #ECEFF4
    7. #8FBCBB
    8. #88C0D0
    9. #81A1C1
    10. #2BA15D
    11. #BF616A
    12. #656B73
    13. #EBCB8B
    14. #A3BE8C
    15. #B48EAD