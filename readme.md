# Norwegian MacBook Pro keyboard layout for Ubuntu

First and foremost, credit to Ole Bakstad who wrote the original upon which this is based. His version used to be hosted on http://dibon.net/wordpress/norwegian-mac-keyboard-layout-in-ubuntu/, but seems to have disappeared. The installations instructions, with the exception of Step 2, is copied verbatim from his blog post. Step 2 is a rewrite that is specific for Norwegian MacBook Pro keyboards.


## How to install

For the last years I’ve been using Mac OS X, but now I’m running Ubuntu. Ubuntu has very much functionality build in, but the Norwegian mac keyboard layout isn’t that great out of the box.

There are three steps required to get the layout partially[NB!] right:

Change 3rd level chooser and switch Alt / Win (cmd) key.
Edit the XKB-file to get keys right.
Set the keyboard in  Ubuntu to “Norway Macintosh”
Step 1:
Open the keyboard settings (System -> Preferences -> Keyboard) and click the “Layouts” tab. Then click the “Other options…” button.

1.1) Press “Alt/Win key behavior” and choose “Left Alt is swapped with left Win-key”.
1.2) Press “Third level choosers” and select “Press any of Alt keys to choose 3rd level” (or “Press left Alt keys to choose 3rd level”).

Step 2:

Backup */usr/share/X11/xkb/symbols/no* as you see fit. Copy the *no* file
included in this package to */usr/share/X11/xkb/symbols/*. Ie:

```Shell
sudo mv /usr/share/X11/xkb/symbols/no /usr/share/X11/xkb/symbols/no.bak
sudo cp no /usr/share/X11/xkb/symbols/no
```

Step 3:
The only thing remaining is to select “Norwegian Macintosh” as your default keyboard layout.
In System -> Preferences -> Keyboard, press the “Layouts”-tab and press the “+”-button.

If everything is done right you should have the basic Norwegian mac layout.

