[default]: https://github.com/ggkovacs/hungarian-pro-v2/blob/master/images/default.png
[option]: https://github.com/ggkovacs/hungarian-pro-v2/blob/master/images/option.png
[capslock]: https://github.com/ggkovacs/hungarian-pro-v2/blob/master/images/capslock.png

# Hungarian PC keyboard layout for macOS

Based on Hungarian PRO layout v2 by Gergely Kovács: https://github.com/ggkovacs/hungarian-pro-v2

## Install

Copy `hungarian_pc.keylayout` and `hungarian_pc.icns` to `~/Library/Keyboard Layouts`. Do NOT copy to the system-wide directory suggested by earlier HOWTO documents (`/Library/Keyboard Layouts`), as since MacOS 12.4 this is not working properly, for some application the layout might be unavalable and may cause unintended layout changes (eg. when switching to Safari, where the layout would not be availble for some reason)


Then ensure the ownership of the files and permissions are set up properly.

```sh
cp hungarian_pc.* ~/Library/Keyboard\ Layouts
sudo chown "$USER" ~/Library/Keyboard\ Layouts/hungarian_pc.*
sudo chgrp staff ~/Library/Keyboard\ Layouts/hungarian_pc.*
sudo chmod u+rwx ~/Library/Keyboard\ Layouts/hungarian_pc.*
```

> source by https://apple.stackexchange.com/questions/300606/keyboard-layout-keeps-reverting-since-upgrade-to-high-sierra

## Keyboard layout

**Default**

![Default layout][default]

**Option**

![Option layout][option]

**Caps lock**

![Caps lock layout][capslock]
