# Norwegian MacBook Pro keyboard layout for Ubuntu

## How to install

Follow the instructions mentioned
[here](http://dibon.net/wordpress/norwegian-mac-keyboard-layout-in-ubuntu/),
but instead of **Step 2** do the following:

Backup */usr/share/X11/xkb/symbols/no* as you see fit. Copy the *no* file
included in this package to */usr/share/X11/xkb/symbols/*. Ie:

```Shell
sudo mv /usr/share/X11/xkb/symbols/no /usr/share/X11/xkb/symbols/no.bak
sudo cp no /usr/share/X11/xkb/symbols/no
```

