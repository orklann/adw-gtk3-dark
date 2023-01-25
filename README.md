# Original theme
https://github.com/lassekongo83/adw-gtk3

# How to
1. Extract the folder to ~/.local/share/themes/ (or /usr/share/themes if you want to install it for all users.)
2. Run this comamnd to set the theme
```shell
gsettings set org.gnome.desktop.interface gtk-theme 'adw-gtk3-dark' && gsettings set org.gnome.desktop.interface color-scheme 'prefer-dark'
```

# Top bar menu popup background is not correct
Set shell theme to Yaru Dark as well in Gnome Tweak

# Flatpak app does not work with this theme

But we have some workaround to use original theme for flatpak app.

```shell
flatpak install org.gtk.Gtk3theme.adw-gtk3 org.gtk.Gtk3theme.adw-gtk3-dark
```
