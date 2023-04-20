# desktop-config

dotfiles for my custom desktop environment

![screenshot](https://user-images.githubusercontent.com/22794371/233259730-1b22258e-7659-4426-b80a-7ad83d156964.png)

i run hyprland, waybar, dunst, fuzzel, and kitty on gnu/linux centered around consistent use of the Dracula color scheme. i use this config acros my laptop and desktop computers and it's been working quite well for me. i have a fairly customized hotkey setup: roughly, the emoji picker is invoked with mod4-alt-space. menu is invoked with either 3-finger swipe up or mod4+space. mod4+esc is window close. mod4+esc opens a terminal. key + gesture binds are configured in `hyprland.conf` and `fusuma/config.yml` respectively.

this desktop environment depends on several arch linux packages:

`yay -S hyprland-autoname-workspaces-git hyprland-hidpi-xprop-git waybar-hyprland xdg-desktop-portal-hyprland hyprpaper kitty kitty-shell-integration kitty-terminfo waybar-hyprland waybar-mpris-git dunst fuzzel ruby-fusuma wofi-emoji-git nwg-look dracula-gtk-theme ttf-lato ttf-iosevka-nerd awesome-terminal-fonts`

this is mainly here for my own use as an offsite backup, so it's bound to be messy in some places.

to install, copy the contents of this repo in `~/.config`.
