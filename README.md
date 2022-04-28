# Dotfiles

Based on https://github.com/f3liperamos/dotfiles project 🏆

## Install dependencies

### Main stuff
> $ brew install curl stow

### ZSH
> $ brew install zsh

### Create `.zshrc.local` file to store local variables
> echo $HOME/.zshrc.local

### Install romkatv/zsh4humans
[zsh4humans](https://github.com/romkatv/zsh4humans/)

### Create <folder> symbolic link to `$HOME`
Use [stow](https://www.gnu.org/software/stow)
> $ man stow

tl;dr
> $ stow -Rv \<folder\>

### Make `.zshrc` also read configs from `.my-zshrc`
> $ echo 'source $HOME/.my_zshrc' >> ~/.zshrc
