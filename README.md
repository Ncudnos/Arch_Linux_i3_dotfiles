# Install everything else
```
sudo pacman -S --needed git base-devel
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
yay -Syyu git curl gcc openjdk-jdk python-neovim neovim nodejs npm python-pyx python-pip zip unzip rar flameshot brillo brave-bin lsd pdftk tldr xournalpp tlp ufw ttf-hack-nerd
ttf-ms-fonts libreoffice-fresh pamac-tray numlockx volumeicon feh xfce4-power-manager archlinux-tweak-tool alacritty rofi thunar thunar-volman thunar-archive-plugins alsa-utils pulseaudio pavucontrol picom fastfetch ibus ibus-bamboo obs-studio mpv lxappearance everforest-gtk-theme-git papirus-nord xarchiver nordzy-icon-theme-git

```

```
sudo ufw limit 22/tcp
sudo ufw allow 80/tcp
sudo ufw allow 443/tcp
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw enable

```

# Set user video role

```
sudo usermod -aG video <username>

```
