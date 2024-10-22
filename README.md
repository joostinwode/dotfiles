# My Dotfiles

These are my dotfiles 

## Requirements 

### Git

### Stow

### Window Manager
```
Sway
pacman -S sway
apt install sway
```

### Clipboard
```
Clipman
pacman -S clipman
apt install clipman
```

### Blue Light Filter
```
Gammastep
pacman -S gammastep
apt install gammastep
```

### Notifications
```
Mako
```
### Status Bar
```
Waybar
pacman -S waybar
apt install waybar
```

### Screenshot
```
Grimshot

Print captures the whole system.

Alt+Print captures the active window.

Ctrl+Print lets you screenshot a selected area.
```

### Settings
```
Swaysettings
Configures sway using a GUI
```

### Autotiling
```
Automatically tiles your new window
```

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



