# About :bulb:  
A set of dotfiles created to be used with **stow**. Different categories of configuration files for setting up an Ubuntu.
Includes:
- **Fonts**
- **Themes**
- **Background images**
- **Bashrc configuration**
- **Zshrc configuration (themes, plugins and more)**
- **Vscode configuration profile**
- **Git profile**
Mostly used and updated from an Ubuntu. But it should work with most Debian based linux distros.

<br />
<br />
<br />

# Requirements :exclamation: 
## Shell :space_invader:
- **ZSH shell**
- **OhMyZsh Framwork**
- **Custom fonts**
- **Powerlevel 10k theme**
- **Curl**
- [**Stow**](https://github.com/malc-j/.dotfiles/tree/main/docs/stow.md)
## Desktop :computer:  
- **gnome-tweaks**
- **Extension manager**
- **Color Palette**

<br />
<br />
<br />

# Getting started :white_check_mark:
##  Resources :briefcase:
This sections covers the structure of the repository, and the different categories of resources.
### Repository
Start by cloning the repository in your users home directory. If you navigate to the directory of the repository you will see a set of directories.
Each one of theese directories represents a category.
#### Fonts
Here are all the fonts stored. For now I have chosen to only include fonts that other tools and framworks depend on.
Therefore it is very **IMPORTANT** to install these fonts before installing **p10k/powerlevel10k**.
For now just navigate to *./notes* inside of the repository's directory, and install all the fonts by clicking them.
#### Themes
A few hand picked themes.
#### Icons
A few icons that goes well with the themes.
#### Configs
Here are all the different configuration files. These can all be synced att the same time or one by one with **stow**.
#### Backgrounds
Just different background. Nothing more. Nothing Less.
#### Docs 
Additional dokumentation.

<br>
<br>

## Shell :space_invader:
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

**Source:**
https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#meslo-nerd-font-patched-for-powerlevel10k

Now just restart the terminal and the interactive configuration will start automatically.
If it doesnt, run this command: `p10k configure`
<br>
<br>

## Desktop :computer:
### Palettes
These are some nice pallettes that can be used when customizing the shell.
Each list shows the index position in palette and HEX code the color.
- **Nord**
0. **#2E3440**
1. **#2B303C**
2. **#3F8062**
1. **#4C566A**
2. **#D8DEE9**
3. **#E5E9F0**
4. **#ECEFF4**
5. **#8FBCBB**
6. **#88C0D0**
7. **#81A1C1**
8.  **#2BA15D**
9.  **#BF616A**
10. **#656B73**
11. **#EBCB8B**
12. **#A3BE8C**
13. **#B48EAD**