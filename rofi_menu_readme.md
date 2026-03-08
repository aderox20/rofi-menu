# Rofi Menu Dotfiles

Custom Rofi menu for XFCE and Sway, with Fastfetch, Nerd Font icons, and additional system tools.

---

## Needed Packages

These are the packages required to run the Rofi menu and its features.

**Debian / Ubuntu / Pop!_OS**
```bash
sudo apt update
sudo apt install rofi alacritty foot fastfetch nautilus pavucontrol blueman xfce4-settings-manager xfce4-taskmanager network-manager-gnome
```

**Arch / Manjaro**
```bash
sudo pacman -Syu rofi alacritty foot fastfetch nautilus pavucontrol blueman xfce4-settings-manager xfce4-taskmanager networkmanager
```

> Copy and paste the commands in your terminal to install everything needed.

---

## Features

- **Terminal shortcut** (``)  
- **File manager** (``)  
- **Applications launcher** (`󰀻`)  
- **Fastfetch menu** (``) with distro-specific options and custom ASCII  
- **System tools** (``)  
- **Audio controls** (``)  
- **Network manager** (``)  
- **Power menu** (``)  

---

## Installation

1. Clone your dotfiles repo:
```bash
git clone https://github.com/aderox20/rofi-menu.git ~/.config/rofi-menu
```

2. Make the menu executable:
```bash
chmod +x ~/.config/rofi-menu/rofi-menu
```

3. Run it:
```bash
~/.config/rofi-menu/rofi-menu
```

---

## Notes

- Works on **XFCE** (uses Alacritty) and **Sway** (uses Foot) automatically.  
- Uses **Nerd Fonts** for icons; make sure your font supports them.  
- Fastfetch submenu has **Default, popu