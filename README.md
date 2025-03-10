# Force Phone Mode (with Quick Toggle)
A fork of https://github.com/vixalien/force-phone-mode that adds a quick toggle to the quick settings

This is an extension that forces the phone mode on GNOME Shell Mobile. Useful
for testing GNOME Shell Mobile on non-mobile devices.

Note that this extension will only work on
[GNOME Shell Mobile](https://gitlab.gnome.org/verdre/mobile-shell) and will
crash with the following error on normal GNOME:

```
Main.layoutManager._updateIsPhone is not a function
```

## Install

To install this extension, clone this repo into `~/.local/share/gnome-shell/extensions/force-phone-mode@phildevprog.com`.

```sh
git clone https://github.com/phildevprog/force-phone-mode.git ~/.local/share/gnome-shell/extensions/force-phone-mode@phildevprog.com
```

## Update

```sh
cd ~/.local/share/gnome-shell/extensions/force-phone-mode@phildevprog.com && git pull
```

## Uninstall

```sh
rm -rf ~/.local/share/gnome-shell/extensions/force-phone-mode@phildevprog.com
```
