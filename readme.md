# Norwegian MacBook Pro keyboard layout for Ubuntu

Note - keyboard with numpad.

Credit to Ole Bakstad who wrote the original upon which this is based.

## How to install

### Step 1 Setting the global options

  * Open the keyboard settings (System -> Preferences -> Keyboard) and click the “Layouts” tab. Then click the “Other options…” button.
  * Press “Alt/Win key behavior” and choose “Left Alt is swapped with left Win-key”.
  * Press “Third level choosers” and select “Press any of Alt keys to choose 3rd level” (or “Press left Alt keys to choose 3rd level”).

### Step 2 Replacing the Ubuntu Norwegian keyboard file

Backup */usr/share/X11/xkb/symbols/no* as you see fit. Copy the *no* file
included in this package to */usr/share/X11/xkb/symbols/*. Ie:

```Shell
sudo mv /usr/share/X11/xkb/symbols/no /usr/share/X11/xkb/symbols/no.bak
sudo cp no /usr/share/X11/xkb/symbols/no
```

### Step 3 Select Norwegian Macintosh

The only thing remaining is to select “Norwegian Macintosh” as your default keyboard layout.
In System -> Preferences -> Keyboard, press the “Layouts”-tab and press the “+”-button. Select “Norwegian Macintosh” and make sure it's on top of the list (or the only one)

Hit the keyboard icon to verify the layout matches your keyboard.

## Done. Contribute with your tips & tricks

If everything is done right you should have the basic Norwegian mac layout. If you have more suggestions for the "options" page, submit an issue or pull request"

Takk for dine bidrag!
