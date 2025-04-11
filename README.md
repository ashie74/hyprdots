- **Window Manager** > [Hyprland](https://github.com/hyprwm/Hyprland) 🎨 
- **Shell** > [Zsh](https://www.zsh.org) 🐚 
- **Terminal** > [Kitty](https://sw.kovidgoyal.net/kitty/) 🐱
- **Panel** > [Hyprpanel](https://hyprpanel.com/getting_started/installation.html) 💈
- **Launcher** > [Rofi](https://github.com/davatorium/rofi) 🚀 
- **File Manager** > [Nemo](https://github.com/linuxmint/nemo) 🔖 
- **GUI Basic-IDE** > [LazyVim](https://www.lazyvim.org/installation) 🗒️

<details>

 <summary><b>INSTALL LIST</b></summary>

## INSTALLATION (Arch Based Only)

<div align="left">

<details>
  
<summary><h3>Hyprland Stuff</h3></summary>

- Installation using paru and pacman 

```sh
## Hyprland Stuff
sudo pacman -S xdg-desktop-portal-hyprland hyprpicker hyprpaper
paru -S ags-hyprpanel-git hyprshot-git
```

</details>

<details>
<summary><h3>Dependencies</h3></summary>

- For nerd-fonts enter 42 ttf-jetbrains-mono-nerd 

```sh
## Dependencies
sudo pacman -S nwg-look zsh man exa git polkit-kde-agent playerctl qt5-wayland qt6-wayland wtype nerd-fonts noto-fonts-emoji cliphist ark brightnessctl
```

</details>

<details>
<summary><h3>Apps & More</h3></summary>

```sh
## Apps & More
sudo pacman -S neofetch htop viewnior neovim mpv nemo
paru -S rofi-lbonn-wayland rofi-emoji-git zen-browser-bin vscodium-bin
```
- brother-hl1118 package is for brother printer

```sh
## Optional Apps
sudo pacman -S obsidian cups cups-pdf print-manager spotify-launcher steam thunderbird
paru -S brother-hl1118 
```

- how to change papirus folder color [CLICK HERE](https://github.com/catppuccin/papirus-folders) 

```sh
## Theme Base
paru -S catppuccin-gtk-theme-mocha papirus-icon-theme papirus-folder-catppuccin-git
```

```sh
### Pipewire
sudo pacman -S pipewire pipewire-alsa pipewire-audio pipewire-pulse pipewire-jack wireplumber gst-plugin-pipewire pavucontrol
```

</details>

</div>

<div align="left">
