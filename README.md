# dotfilesroatfr
dotfiles + wallpaper + scripts for the rice on Reddit fr


WALLPAPER
-wallpaper file is at ./wallpaper



INSTALL AWESOME WM

apt-get update
apt install awesome

pacman -Sy
pacman -S install awesome




** if you use ANY of the following commands, open a terminal in the same directory of THIS readme FIRST, or else none of them will work. **



AWESOME CONFIG

cp -r .config/awesome ~/.config
-the config file is at ./.config/awesome/rc.lua


INSTALL AWESOME THEME
cp -r themes /usr/share/awesome/



INSTALL BATTERY INDICATOR SCRIPT
cp ./bat ~/



INSTALL MEMORY INDICATOR SCRIPT
cp ./ram2 ~/



INSTALL XFCE4-PANEL

apt-get update
apt install xfce4-panel

pacman -Sy
pacman -S xfce4-panel

-color of panel is #2C1F51




SUCKLESS TERMINAL THEME

Config file for st is st/config.h
-To install, open a terminal in st directory, and type $ make clean install



GTK THEME

Midnight Green
https://store.kde.org/p/1273208/
