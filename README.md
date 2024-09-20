# sway

My sway window manager config, based on the [Catppuccin] theme. Includes themeing for [Waybar]. 

# Installation

## Basic Way

Clone the repo to your system. Move the `sway` and `waybar` directories to your `~/.config` directory.

## Local Development

Clone the repo to your favorite local `development` directory. Use the [GNU] [stow] utility to setup symbolic links in your `~/.config` directory. 

``` sh
git clone https://github.com/TylerDurham/dtd-sway.git

cd dtd-sway

stow -S sway -t ~/
stow -S waybar -t ~/
```

# Uninstall

To uninstall, symply remove the symbolic links in your `~/.config` directory.

``` sh
rm ~/.config/sway
rm ~/.config/waybar
```

[GNU]: https://www.gnu.org/
[stow]: https://www.gnu.org/software/stow/
[Catppuccin]: https://catppuccin.com/
[Waybar]: https://github.com/Alexays/Waybar 
