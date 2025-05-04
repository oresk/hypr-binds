This script displays all the binds that are setup in your hyprland config. I use this in conjunction with this config to display a sort of a cheat sheet of my binds when I want to look something up. I create the popup by using this config:

```
# display binds
bind = $mainMod, G,  togglespecialworkspace, binds
workspace = special:binds, gapsout:150, on-created-empty:alacritty --option font.size=10 --option window.opacity=0.75 --command  ~/.config/scripts/hypr-binds/hypr-binds.py -w
workspace = special:binds, decoration:dim_special:0.1
```
