# Rofi Menu 

Custom Rofi menu for XFCE and Sway, Nerd Font icons, and additional system tools.

---

## Needed Packages

These are the packages required to run the Rofi menu and its features.

**Debian-based / Ubuntu / Pop!_OS**
```bash
sudo apt update
sudo apt install rofi alacritty foot fastfetch nautilus pavucontrol blueman xfce4-settings-manager xfce4-taskmanager network-manager-gnome
```

**Arch-based**
```bash
sudo pacman -Sy rofi alacritty foot fastfetch nautilus pavucontrol blueman xfce4-settings-manager xfce4-taskmanager networkmanager
```

> Copy and paste the commands in your terminal to install everything needed.

> If you're going to set up sway/any wayland DE/WM update rofi because older rofi versions do not support wayland and you would need to update rofi || install rofi-wayland

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
4. (optional) Put it on path:
```bash
export PATH="$HOME/.config/rofi-menu:$PATH"
```

---

## Notes

- Works on **XFCE** (uses Alacritty) and **Sway** (uses Foot) automatically.  
- Uses **Nerd Fonts** for icons; make sure your font supports them.  
