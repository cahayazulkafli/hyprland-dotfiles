
# Dotfiles for Hyprland, a dynamic Wayland compositor.

Hyprland dotfiles for Arch Linux. Experimenting with Wayland to see if it is better for gaming or not.

## Prerequisites

- hyprland (the compositor)
- hyprpaper (setting up wallpaper, made by the hyprland team)
- wofi (run menu)
- waybar (a bar... like polybar)
- alacritty (terminal)

## Installation

**1. Install the prerequisites:**

```
sudo pacman -Syu hyprland wofi waybar alacritty hyprpaper
```

**2. Git clone this repository:**

```
git clone https://www.github.com/cahayazulkafli/hyprland-dotfiles.git
```

**3. And then move the files into the `.config` folder:**

```
cd hyprland-dotfiles && mv * ~/.config
```

**Done! Adjust to your needs.**
