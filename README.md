# EndeavourOS Hyprland Clean Install

## First commands
```bash
sudo pacman -S hyprland kitty sddm nvim zsh yay
yay -S pipewire pipewire-pulse pavucontrol xdg-desktop-portal-hyprland thunar nwg-look arc-gtk-theme-eos rofi-wayland waybar network-manager-applet dunst
sudo systemctl enable sddm.service
sudo systemctl start sddm.service
```

## Start Pipewire
```bash
systemctl --user start pipewire
systemctl --user start pipewire-pulse
```

## Put in the Hyprland conf exec-once
- dbus-update-activation-environment --systemd WAYLAND_DISPLAY XDG_CURRENT_DESKTOP
- waybar
- nm-applet


