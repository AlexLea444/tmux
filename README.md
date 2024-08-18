### TMUX CONFIG
Alex Lea

This repository stores my current(ish) tmux config for easy use.
This repository is almost entirely copied from [this great video](https://www.youtube.com/watch?v=DzNmUNvnB04) by Dreams of Code.

# Requirements
It should go without saying that this config will only work if Tmux is installed.
View the official docs for an installation guide.

This config requires Tmux Plugin Manager, ```tpm```, for installing and managing plugins.
To install the plugins, use ```prefix``` + ```I```. Note that the default prefix is
```C-b``` (```ctrl``` + ```b```), but this config changes it to ```C-s```(```ctrl``` + ```s```). When following the Installation guide below,
```C-s``` should be used as ```prefix```.

# Installation
To load, clone the repository to your ```.config``` directory. 

0. Close out of any previous tmux sessions.
1. Install this config file and tpm:
```bash
$ git clone git@github.com:AlexLea444/tmux.git ~/.config/tmux
$ git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm
$ tmux
```
2. Press ```prefix``` + ```I``` to fetch plugins.
