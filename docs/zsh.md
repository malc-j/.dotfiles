# Shell
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