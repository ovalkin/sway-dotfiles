# Sway rice
![Screenshot 1 ](https://github.com/ovalkin/sway-dotfiles/blob/main/0.png)

## Dependencies
```
sudo pacman -S sway kitty wofi ly slurp swappy grim wl-clipboard waybar swaybg networkmanager pipewire pipewire-alsa pipewire-pulse autotiling pavucontrol terminus-font brightnessctl zsh adw-gtk-theme amd-ucode polkit-kde-agent qt5ct qt6ct swayidle
yay -S swaykbdd swaylock-effects sway-audio-idle-inhibit-git 
```
Font: https://github.com/subframe7536/maple-font

## Config
### LY
Copy `ly` to `/etc/ly`
Run `sudo systemctl enable ly@tty2.service`
Configure fonts in `/etc/vconsole.conf` // my choice is ter-u22b

### GTK
Run `gsettings set org.gnome.desktop.interface gtk-theme 'adw-gtk3'`

### Qt5/6
Set env variable to `QT_QPA_PLATFORMTHEME=qt5ct:qt6ct`
