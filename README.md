### TMUX CONFIG
Alex Lea

This repository stores my current(ish) tmux config for easy use.

# Requirements
It should go without saying that this config will only work if Tmux is installed.
View the official docs for an installation guide.

This config requires Tmux Plugin Manager, ```tpm```, for installing and managing plugins.
To install the plugins, use ```prefix``` + ```I```. Note that the default prefix is
```<c-b>```, but this config changes it to ```<c-s>```, so order-of-operations might require
you to use one prefix or the other during setup.

# Installation
To load, clone the repository to your ```.config``` directory. 

1. Install this config file and tpm:
```bash
$ git clone git@github.com:AlexLea444/tmux.git ~/.config/tmux
$ git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm
$ tmux
```
2. Press ```prefix``` + ```I``` to fetch plugins.
