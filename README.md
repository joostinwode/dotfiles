![2024-10-21T18:51:39,030609303-07:00](https://github.com/user-attachments/assets/d61983f0-e104-4338-8968-e70d1f2a4ae2)

# My dotfiles 

## Installation

First, check out the dotfiles rpeo in your $HOME directory using git

```
$ git clone https://github.com/joostinwode/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```

## Requirements 

### Git
```
pacman -S git
apt install git
```

### Stow
```
pacman -S stow
apt install stow
```
### Application Launcher
```
pacman -S dmenu
apt install dmenu
```

### Window Manager
```
pacman -S sway
apt install sway
```

### Clipboard
```
pacman -S clipman
apt install clipman
```

### Blue Light Filter
```
pacman -S gammastep
apt install gammastep
```

### Notifications

https://github.com/emersion/mako.git

### Status Bar
```
pacman -S waybar
apt install waybar
```

### Screenshot
```
pacman -S grimshot
apt install grimshot
```
Print captures the whole system.

Alt+Print captures the active window.

Ctrl+Print lets you screenshot a selected area.

### Settings

Swaysettings
configures sway using a GUI

https://github.com/ErikReider/SwaySettings.git

### Autotiling

Automatically tiles your new window

https://github.com/nwg-piotr/autotiling.git

## Required Fonts

NotoSans
JetBrainsMono

