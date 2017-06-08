# iOS 10

iOS 10 theme for Linux desktops, for the moment only available for Unity and Cinnamon

![ios-10](http://b00merang.weebly.com/uploads/1/6/8/1/16813022/screenshot-2017-02-04-23-33-54_orig.png)


**Maintainer :** [Elbullazul](https://github.com/Elbullazul)

**Distributor :** [B00merang Project](https://github.com/B00merang-Project)

**License :** GPL v3

**More info :** http://b00merang.weebly.com/ios-10.html

### Manual installation ###

Extract the zip file to the themes directory i.e. `/home/USERNAME/.themes`

To set the theme in Gnome, run the following commands in Terminal,

```
gsettings set org.gnome.desktop.interface gtk-theme "iOS"
gsettings set org.gnome.desktop.wm.preferences theme "iOS"
```

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "iOS"
```

### Requirements ###

- GTK+ 3.6 or above
- Murrine and Pixmap theme engines

### Contribute ###

Contact us @ http://b00merang.weebly.com/contact.html
