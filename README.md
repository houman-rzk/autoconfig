# autoconfig

# WARNING: This package is currently under maintenance. Run at your own peril.

A script for automating the installation and configuration of my powerful daily driver system based on Arch Linux.

Originally inspired by [LARBS](https://larbs.xyz), it provides a much deeper configuration of many programs, practically evolving into a just-works distro.

This script deploys [my dotfiles](https://github.com/houman-rzk/dotfiles) and configures a system that revolves vim and dwm.

## Installed software
- dwm
- st
- dmenu
- dwmblocks
- lf
- zsh
- mpv
- mpd and ncmpcpp
- nsxiv

## Warning
The script is intended to run on a freshly installed Arch Linux system, **running it as is will delete the contents of your home directory.**

## Instructions
```
git clone https://github.com/houman-rzk/autoconfig /tmp/autoconfig
sudo sh /tmp/autoconfig/autoconfig
```
