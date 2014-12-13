b-theme is a modern flat theme with a combination of light and dark elements.


### Manual installation

Extract the zip file to the themes directory i.e. `/usr/share/themes/`

To set the theme in Gnome, run the following commands in Terminal,

```
gsettings set org.gnome.desktop.interface gtk-theme "bTheme"
gsettings set org.gnome.desktop.wm.preferences theme "bTheme"
```

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "bTheme"
xfconf-query -c xfwm4 -p /general/theme -s "bTheme"
```

### Code and license

License: GPL-3.0+
