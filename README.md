# Hypr0x
Collection of Dot Config Files for Hyprland with a Simple Install Script for a Fresh Arch Linux Setup Using Yay
```
yay -S hyprland-bin kitty polybar swww \
swaylock-effects wofi wlogout mako xdg-desktop-portal-hyprland-git \
swappy grim slurp nautilus polkit-gnome python-requests pamixer \
pavucontrol brightnessctl bluez bluez-utils blueman \
network-manager-applet gvfs nautilus-archive file-roller btop \
pacman-contrib starship ttf-jetbrains-mono-nerd ttf-jetbrains-mono noto-fonts-emoji \
lxappearance xfce4-settings sddm-git sddm-sugar-candy-git
```

Or you can use the attached script "set-hypr" to install everything for you.

Below is a list of the packages that will be installed:`

hyprland-bin: The Hyprland compositor.

kitty: The default terminal.

polybar: A highly customizable status bar for Wayland or X11.

swww: Used to set a desktop background image.

swaylock-effects: A fork of Swaylock that adds additional visual effects for locking the desktop.

wofi: An application launcher menu.

wlogout: A logout menu that allows for shutdown, reboot, and sleep.

mako: A graphical notification daemon.

xdg-desktop-portal-hyprland-git: The xdg-desktop-portal backend for Hyprland.

swappy: A screenshot editor tool.

grim: A screenshot tool for Wayland, captures images from a Wayland compositor.

slurp: A screenshot tool that helps select a region in Wayland.

nautilus: A graphical file manager.

polkit-gnome: Needed to request superuser access for some graphical applications.

python-requests: Required for the weather module script to execute.

pamixer: For controlling audio settings such as volume.

pavucontrol: A GUI for managing audio and audio devices.

brightnessctl: Used to control monitor and keyboard brightness levels.

bluez: The Bluetooth service.

bluez-utils: Command-line utilities for interacting with Bluetooth devices.

blueman: A graphical Bluetooth manager.

network-manager-applet: An applet for managing network connections.

gvfs: Adds missing functionality to Thunar, such as automounting USB drives.

file-roller: A set of tools for working with compressed files (zip, tar, etc.).

btop: A resource monitor that shows usage and stats for the processor, memory, disks, network, and processes.

pacman-contrib: Adds additional tools for Pacman, needed for displaying system updates in Waybar.

starship: A customizable shell prompt.

ttf-jetbrains-mono-nerd: A Nerd Font for icons and overall appearance.

noto-fonts-emoji: Fonts required by the weather script in the top bar.

lxappearance: A tool for setting the GTK theme.

xfce4-settings: A set of tools for XFCE, needed to set the GTK theme.

sddm-git: The development version of SDDM (Simple Desktop Display Manager) for graphical login.

sddm-sugar-candy-git: A custom SDDM theme (based on a copy of the Sugar Candy theme).
