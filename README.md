
# 💠 Setup

<img align="center" src="https://github.com/ashie74/wallpapers/blob/main/screenshots/wall.png">

<details>
  
<summary><h3>🗨️ More</h3></summary>

<img align="center" src="https://github.com/ashie74/wallpapers/blob/main/screenshots/tilles.png">

<img align="center" src="https://github.com/ashie74/wallpapers/blob/main/screenshots/flode.png">

<img align="center" src="https://github.com/ashie74/wallpapers/blob/main/screenshots/notific.png">

</details>


<details>

<summary><h3>⌨️ Basic keybinds</h3></summary>

- open terminal (kitty): **SUPER + ENTER**
- eixt to login manager (ly): **CTRL + SHIFT + Q** 
- close active window: **ALT + Q**
- toggle to float and tile: **ALT + W**
- open file manager (nemo): **SUPER + E**
- open launcher (rofi): **SUPER + D** 

---

_More Keybins in ~/.config/hypr/keybinds.conf_

</details>

<details>

<summary><h3>ℹ️ Info</h3></summary>

- Operating System: **EndeavourOS** 🪐
- Window Manager: **Hyprland** 🎨
- Status Bar: **Hyprpanel** 🚥
- Terminal: **kitty** 🐱
- Launcher: **rofi** 🚀
- Browser: **Zen Browser** (with BetterFox) 🦊
- File Manager: **nemo** 🗃️
- Image Viewer: **viewnior** 🖼️
- Video Player: **mpv** 🎬
- Graphic Editor: **GIMP** (with PhotoGIMP) 🖌️
- Lockscreen: **Swaylock** 🔒
- Fonts: **JetBrains Mono Nerd Font** 🔠

</details>

## INSTALLATION (Arch Based Only)

<div align="left">

<details>
  
<summary><h3>Hyprland Stuff</h3></summary>

- _Installation using paru and pacman_
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

- _For nerd-fonts enter 42 ttf-jetbrains-mono-nerd_ 
- _systemctl enable ly.service (enable Login Manager) | move ly folder to /etc/ly/_

```sh
sudo pacman -S nwg-look ly zsh man exa git polkit-kde-agent playerctl qt5-wayland qt6-wayland wtype nerd-fonts noto-fonts-emoji cliphist ark brightnessctl
```

</details>

<details>
<summary><h3>Apps & More</h3></summary>

- _LazyVim [GET HERE](https://www.lazyvim.org/installation) (neovim config)_
- BetterFox [GET HERE](https://github.com/yokoffing/Betterfox/blob/main/user.js)

```sh
sudo pacman -S neofetch htop mpv neovim viewnior nemo
```
```sh
paru -S rofi-lbonn-wayland rofi-emoji-git zen-browser-bin vscodium-bin
```

## Optional Apps

- _obsidian setup [GET HERE](https://github.com/ashie74/obsidian-dotfile)_
- _GIMP = PhotoGIMP [GET HERE](https://github.com/Diolinux/PhotoGIMP)_
- _brother-hl1118 package is for brother printer_



```sh
sudo pacman -S obsidian cups cups-pdf print-manager spotify-launcher steam thunderbird gimp
```
```sh
paru -S brother-hl1118 
```

## Theme Base

- _how to change papirus folder color [GET HERE](https://github.com/catppuccin/papirus-folders)_ 

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
- bar inspiration -> [PewDiePie](https://www.youtube.com/watch?v=pVI_smLgTY0&t=1071s)
