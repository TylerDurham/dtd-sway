# sway
My sway window manager config. 

# Installation

## Basic Way

Clone the repo to your system. Move the `sway` and `waybar` directories to your `~/.config` directory.

## Local Development

Clone the repo to your $HOME directory. Use the [GNU] [stow] utility to setup symbolic links in your `~/.config` directory. 

``` sh
git clone https://github.com/TylerDurham/dtd-sway.git

cd ~/dtd-sway

stow -S sway -t ~/
stow -S waybar -t ~/
```

[GNU]: https://www.gnu.org/
[stow]: https://www.gnu.org/software/stow/
