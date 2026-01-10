# dotfiles

Personal Arch Linux + Hyprland dotfiles, developed mainly in a VirtualBox VM and intended to be moved to bare metal later.

This repo is **not an install script**. It’s a reference for how my system is configured.

---

## What this is

- Hyprland (Wayland compositor)
- Waybar
- Rofi
- SwayNC
- PipeWire audio
- Thunar
- SDDM
- Fish shell

Focused on usability first, visuals second.

---

## Layout
hypr/ Hyprland config (modular)
waybar/ Waybar config + CSS
swaync/ Notifications
fish/ Shell config
system/
packages.txt Pacman packages I actually use
enabled-services.txt Systemd services I intentionally enabled

---

## Notes

- Nothing here installs packages or enables services automatically
- `system/` files are documentation, not automation
- Currently only contains core workflow stuff, no UI or aesthetics yet
