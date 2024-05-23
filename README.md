# Arch w/ Hyprland installation guide

1. Download Arch Linux Image from - [<u>\*official site\*</u>](https://archlinux.org/download/)
2. Use [<u>Ventoy</u>](https://www.ventoy.net/en/index.html) to make bootable-usb device
3. Boot from Arch Linux Image and set up it for urself with ***archinstall*** script ![](https://i0.wp.com/www.lorenzobettini.it/wp-content/uploads/2022/07/archinstall-2.png?ssl=1)
4. **`sudo pacman -Syu`** - to update ur system
5. **`sudo pacman -S git`** - to install git
6. **`git clone https://aur.archlinux.org/yay.git`** - to download [<u>yay</u>](https://aur.archlinux.org/packages/yay)
7. **`cd yay`** - to open folder with **yay**
8. **`makepkg -si`** - to install **yay**

# Heeeere we go - packages!

1. [**Hyprland**](https://archlinux.org/packages/extra/x86_64/hyprland/) - a highly customizable dynamic tiling Wayland compositor, to install use: **`sudo pacman -S hyprland`**
2. [**Waybar**](https://archlinux.org/packages/extra/x86_64/waybar/) - highly customizable Wayland bar for Sway and Wlroots based compositors, to install use: **`sudo pacman -S waybar`**
3. [**Swaybg**](https://archlinux.org/packages/extra/x86_64/swaybg/) - wallpaper tool for Wayland compositors, to install use: **`sudo pacman -S swaybg`**
4. [**Pavucontrol**](https://archlinux.org/packages/extra/x86_64/pavucontrol/) - PulseAudio Volume Control, to install use: **`sudo pacman -S pavucontrol`**
5. [**Alacritty**](https://wiki.archlinux.org/title/Alacritty) - is a simple, GPU-accelerated terminal emulator written in Rust, to install use: **`sudo pacman -S alacritty`**
6. [**Nevim**](https://wiki.archlinux.org/title/Neovim) - s a fork of [**Vim**](https://wiki.archlinux.org/title/Vim) aiming to improve the codebase, allowing for easier implementation of APIs, improved user experience and plugin implementation, to install use: **`sudo pacman -S neovim`**
7. [**Rofi**](https://wiki.archlinux.org/title/Rofi) - s a window switcher, run dialog, ssh-launcher and dmenu replacement, to install use: **`sudo pacman -S rofi-wayland`**
8. [**Thunar**](https://wiki.archlinux.org/title/thunar) - file manager, to install use: **`sudo pacman -S thunar`**
9. [**Firefox**](https://archlinux.org/packages/extra/x86_64/firefox/) - standalone web browser from mozilla.org, to install use: **`sudo pacman -S firefox`**
10. [**Fastfetch**](https://archlinux.org/packages/extra/x86_64/fastfetch/) - like [**Neofetch**](https://archlinux.org/packages/extra/any/neofetch/), but much faster because written in C, to install use: **`sudo pacman -S fastfetch`**
11. [**Vesktop**](https://aur.archlinux.org/packages/vesktop-bin) - a cross platform electron-based desktop app aiming to give you a snappier Discord experience with **Vencord** pre-installed, to install use: **`yay -S vesktop-bin`**
