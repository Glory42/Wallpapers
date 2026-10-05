# wallpapers

The wallpapers of my Arch Hyprland setup. One folder per theme, named like the theme folder in
[arch-config](https://github.com/Glory42/arch-config) (`theme/themes/<name>/`). Which pictures a theme
shows, and which one is its main picture, is set in that theme's `theme.json`, not here.

`arch-config/install.sh` clones this repo to `~/Projects/wallpapers` and links each folder to
`theme/themes/<name>/wallpapers`.

To add a picture: put it in the theme's folder here, add its file name to `wallpapers` in
`theme.json` in arch-config, and push both.
