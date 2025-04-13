# 💠 Setup

<img align="center" src="https://github.com/ashie74/imgs/blob/main/wall.png">

<details>
  
<summary><h3>More</h3></summary>

<img align="center" src="https://github.com/ashie74/imgs/blob/main/bar2.png">

---

<img align="center" src="https://github.com/ashie74/imgs/blob/main/rofi-and-neofetch.png">

---

<img align="center" src="https://github.com/ashie74/imgs/blob/main/tilles.png">

</details>

<details>

<summary><h3>Info</h3></summary>

- Operating System: **EndeavourOS** 👾
- Window Manager: **Hyprland** 🎨
- Status Bar: **Hyprpanel** ➖
- Terminal: **kitty** 🐱
- Launcher: **rofi** 🚀
- Browser: **Zen Browser** (with BetterFox) 🌐
- File Manager: **nemo** 📁
- Image Viewer: **viewnior** 🖼️
- Video Player: **mpv** 🎬
- Lockscreen: **Swaylock** 🔒
- Fonts: **JetBrains Mono Nerd Font** 🔠

</details>

## INSTALLATION (Arch Based Only)

<div align="left">

<details>
  
<summary><h3>Hyprland Stuff</h3></summary>

- Installation using paru and pacman
```sh
sudo pacman -S paru
```

```sh
sudo pacman -S xdg-desktop-portal-hyprland hyprpicker hyprpaper
```
```sh
paru -S ags-hyprpanel-git hyprshot-git
```

</details>

<details>
<summary><h3>Dependencies</h3></summary>

- For nerd-fonts enter 42 ttf-jetbrains-mono-nerd 
- systemctl enable ly.service (enable Login Manager)
- move ly folder to /etc/ly/

```sh
sudo pacman -S nwg-look ly zsh man exa git polkit-kde-agent playerctl qt5-wayland qt6-wayland wtype nerd-fonts noto-fonts-emoji cliphist ark brightnessctl
```

</details>

<details>
<summary><h3>Apps & More</h3></summary>

```sh
sudo pacman -S neofetch htop viewnior neovim mpv nemo
```
```sh
paru -S rofi-lbonn-wayland rofi-emoji-git zen-browser-bin vscodium-bin
```

## Optional Apps

- obsidian setup [CLICK HERE](https://github.com/ashie74/obsidian-dotfile)
- brother-hl1118 package is for brother printer

```sh
sudo pacman -S obsidian cups cups-pdf print-manager spotify-launcher steam thunderbird cava
```
```sh
paru -S brother-hl1118 
```

## Theme Base

- how to change papirus folder color [CLICK HERE](https://github.com/catppuccin/papirus-folders) 

```sh
paru -S catppuccin-gtk-theme-mocha papirus-icon-theme papirus-folder-catppuccin-git swaylock-effects-git
```

### Pipewire
```sh
sudo pacman -S pipewire pipewire-alsa pipewire-audio pipewire-pulse pipewire-jack wireplumber gst-plugin-pipewire pavucontrol
```

</details>

</div>

<div align="left">

---

# 🩷 Thank you to 
- hyprland config based -> [linuxmobile](https://github.com/linuxmobile/hyprland-dots)
- swaylock config based -> [linuxmobile](https://github.com/linuxmobile/hyprland-dots/blob/Sakura/.config/swaylock/config)
- kitty config and zsh config -> [ericmurphyxyz](https://github.com/ericmurphyxyz/dotfiles)
- rofi config based -> [Eric Murphy](https://www.youtube.com/watch?v=v8w1i3wAKiw&t=154s)
- neofetch theme based -> [blockfetch](https://github.com/chick2d/neofetch-themes/blob/main/small/blockfetch.conf)
