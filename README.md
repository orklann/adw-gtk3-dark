### Original theme
https://github.com/lassekongo83/adw-gtk3

### Screenshots
![image](https://i.ibb.co/Jq7nL2C/Screenshot-from-2023-01-25-16-18-04.png)

### How to
1. Extract the folder to ~/.local/share/themes/ (or /usr/share/themes if you want to install it for all users.)
2. Run this comamnd to set the theme
```shell
gsettings set org.gnome.desktop.interface gtk-theme 'adw-gtk3-dark' && gsettings set org.gnome.desktop.interface color-scheme 'prefer-dark'
```

### Top bar menu popup background is not correct
1. Copy rkt theme in folder `gnome-shell-theme` to ~/.themes/
```shell
cp -r gnome-shell-theme/rkt/ ~/.themes/rkt
```
2. Set gnome shell theme to `Rkt` with Gnome Tweak


### Flatpak app does not work with this theme

But we have some workaround to use original theme for flatpak app.

```shell
flatpak install org.gtk.Gtk3theme.adw-gtk3 org.gtk.Gtk3theme.adw-gtk3-dark
```

### Make other apps that takes effects (Calulator, Text Editor ect)
```shell
cp ~/.local/share/themes/adw-gtk3-dark/gtk-3.0/gtk.css ~/.config/gtk-3.0/
cp ~/.local/share/themes/adw-gtk3-dark/gtk-3.0/gtk.css ~/.config/gtk-4.0/
```
