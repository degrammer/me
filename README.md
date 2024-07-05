
# Personal Stuff files

This project contains all my configuration, it contains stuff like dotfiles, my CV, and more things!
Stop starting from scratch when setting up a new Laptop, centralizing this will help you to keep your favorite configuration files in one single place.

![hacker](hacker.png)



# Git Configuration

Please do not create a Git configuration file from scratch, Symlink it with the .gitconfig file from this repository.
Usually, my projects are located at **Documents/degrammer**

If you use this for your setup, change the directory properly.

```bash
ln -s $HOME/Documents/degrammer/me/.gitconfig ~/.gitconfig
```

# Configuring Powerline 11K

My favorite terminal theme is [Powerlevel 10K](https://github.com/romkatv/powerlevel10k) alongside [ohmyzh](https://ohmyz.sh/)

# Configuring Vim

Please do not create a Vim configuration file, Symlink it with the .zshrc file from this repository.

```bash
ln -s $HOME/Documents/degrammer/me/.vimrc ~/.vimrc
```

# Configuring OhMyZsh

```bash
ln -s $HOME/Documents/degrammer/me/.zshrc ~/.zshrc
```
