# About
This is a fork of Luke Smith's dwm config based on suckless' dwm.

all keybindings are in config.h

## Installation
```sh
git clone --depth=1 https://github.com/CD930/dwm
cd dwm/
make clean install
```
## Dependencies
`base-devel`

`libX11`

`libXft`

`libXinerama` **(Only required if you have multiple monitors, if that's the case, edit config.mk).**

`xorg-server`

`xorg-init`

`tcc` **(You can edit config.mk to use the compiler of your preference).**
