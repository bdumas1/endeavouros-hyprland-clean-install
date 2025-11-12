# My EndeavourOS Hyprland Clean Install

I use [EndeavourOS](https://endeavouros.com) with [Hyprland](https://hypr.land) installed with [end-4 dotfiles](https://github.com/end-4/dots-hyprland).

## Installation

- Install [EndeavourOS](https://endeavouros.com) from their iso file
- Select the Gnome environment by default
- Then, [end-4](https://github.com/end-4/dots-hyprland) recommands to use this command to install everything with Hyprland: `bash <(curl -s https://ii.clsty.link/setup)`

- After login on Hyprland, clone my [dotfiles](https://github.com/bdumas1/dotfiles)
- Run `./install`. This script will normally link the `hypr/custom` folder from this dotfiles repo to `~/.config/hypr/custom`

### Add outfoxxed/hy3

```bash
hyprpm update
hyprpm add https://github.com/outfoxxed/hy3
hyprpm enable hy3
```
