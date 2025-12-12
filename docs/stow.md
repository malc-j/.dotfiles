# STOW

## Requirements
### IMPORTANT
**This requires that this repository has been clones, and that zsh is installed and configured.**

## Get Started
### 1. Install stow
Install *stow* by running this command:
`sudo apt-get install stow`

### 2. Navigate to directory
Navigate to the directory of the repository:
`cd .dotfiles/`

### 3. Stow files
In this step you can choose to *stow* all files of this repository or you can *stow* them one by one.
#### 3.1 Stowing all in a category
1. To stow all files from a category, you need to navigate to that category inside of the repo directory. For example (*configs* category):
`cd .dotfiles/configs`
2. Then you need to run the stow command for all directories:
`stow t- ~ *`
#### 3.2 Stowing one directory in a category
1. To stow one directory from a category, you need to navigate to that category inside of the repo directory. For example (*configs* category):
`cd .dotfiles/configs`
2. Then you need to run the stow command for that directory:
`stow t- ~ zshrc`
#### Note
**If you get a warning saying the directory already exists just delete the entire directory and stow again.**

