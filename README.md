# dotfiles for Hyprland

<img width="1920" height="1080" alt="dots-example" src="https://github.com/user-attachments/assets/17c9a648-e182-4cf0-929f-e4b8cac7503a" />

This is a collection of configuration files for my **Arch Linux** + **Hyprland** setup :)

**Keep in mind** that there's no installation script, just the configs.

Wallpaper source -- ```https://wallhaven.cc/w/9oxjvd```

# dependencies
**AUR install helper** -- ```paru```, but you can also use ```yay``` if you wish :)

**Sound engine** -- ```pipewire```, ```wireplumber```

**Login manager** -- ```ly```

**Hyprland itself** -- ```hyprland```, ```uwsm```

**Terminal** -- ```kitty```

**File explorer** -- ```nemo```

**GUI text editor** -- ```xed```

**Top bar** -- ```ashell``` (from *AUR*)

**Apps search** -- ```wofi```

**Wallpaper** -- ```hyprpaper```

**Screenshot manager** -- ```hyprshot```

**GTK 2/3/4 style** -- ```nwg-look```, **Gruvbox-GTK-Theme** by **Fausto-Korpsvart**

**Qt 5/6 style** -- ```qt5ct qt6ct qt5-wayland qt6-wayland kvantum kvantum-qt5 breeze-icons```, **gruvbox-kvantum-themes** by **sachnr**

**System Font** -- ```ttf-fira-mono```, size 11

**Additional game-specific fixes** -- ```gamescope``` (I dont't really use it much but anyways)

**Clipboard manager** -- ```cliphist```

**System info** -- ```fastfetch```

**Logout** -- ```wlogout``` (from *AUR*)

**AirDrop-like thing** -- ```localsend``` (from *AUR*)

# additional changes
1. **Changed a couple bindings**:
   1) ```Super``` + ```Enter``` -- open **kitty** terminal
   2) ```Super``` + ```Q``` -- close active window
   3) ```Super``` + ```Space``` -- open **wofi**
   4) ```Super``` + ```B``` -- open **Firefox**

2. **Added bindings**:
   1) ```PrintScreen``` -- screenshot of a full screen to ```~/Pictures/Screenshots```
   2) ```Shift``` + ```PrintScreen``` -- screenshot of a region to ```~/Pictures/Screenshots```
   3) ```Super``` + ```PrintScreen``` -- screenshot of a full screen to clipboard
   4) ```Super``` + ```Shift``` + ```PrintScreen``` -- screenshot of a region to clipboard

# installation
[ ⚠️ *you have to install **Hyprland**, **uwsm**, **kitty** and **ly** first*. ]

1. Install packages from pacman:

```sudo pacman -S --needed pipewire wireplumber nemo xed wofi hyprpaper hyprshot nwg-look qt5ct qt6ct qt5-wayland qt6-wayland kvantum kvantum-qt5 breeze-icons ttf-fira-mono gamescope cliphist fastfetch```

2. Install ```paru```:

```sudo pacman -S --needed git base-devel && git clone https://aur.archlinux.org/paru.git && cd paru && makepkg -si && cd```

3. Install packages from *AUR* using ```paru```:

```paru -S ashell localsend wlogout```

4. Move config files to your home directory :)

# compatibility
I **do not guarantee** any compatibility with *your* setup, but for me it works perfectly fine on Hyprland 0.51.1 :)
