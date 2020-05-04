DreymaR's Big Bag of Keyboard Tricks (forked)
====================================

### Updates in fork
The goal is to align the layout to be similar to the layout provided by:
[My Dactyl Keyboard](https://github.com/sunshin-es/ergodox-firmware).

Some updates from the original are:
* For the ANSI keyboard the Z is **not** relocated. This makes it similar (in my opinion) to the ergo layout
* The CAPS key is mapped to Escape
* ; and / are also switched from the "standard" Colemak
* Better support for German text entry:
  * AltGr + a/A -> ä/Ä
  * AltGr + o/o -> ö/Ö
  * AltGr + u/u -> ü/Ü
  * AltGr + s   -> ß

### For Linux (updated to [XKB-data v2.23.1-1ubuntu1][XKBdat], 2018-08)

* New "Colemak[eD]" AltGr mappings (lv3-4) putting dead keys on AltGr+symbol keys and reworking most other mappings
* Angle/Wide ergo modifications to improve wrist angles, hand spacing and right pinky stretch/load effort
* Curl(DH) ergo modifications to encourage natural finger curvature
* An "Extend" layer using Caps Lock as a modifier (lv5-8) for navigation/editing from the home position and more
* For several locales, a 'Unified Symbols' layout with only a few necessary changes from the standard Colemak[eD];
  Also, a layout to 'Keep Local Symbols' like their default (QWERTY-type) counterparts for that locale
* Intuitive phonetic layouts for Cyrillic, Greek and Hebrew scripts
* Mirrored Colemak that allows one-handed typing (if I ever break an arm...)
* The 4 Tarmak transitional Colemak layouts for learning Colemak (or Colemak-Curl) in smaller steps if desired

More info
---------

Run the install and setxkb scripts with -h (or look inside them) for more help and info about their workings!


Links
-----

See [DREYMAR'S XKB topic on the Colemak Forums](http://forum.colemak.com/viewtopic.php?id=1438) (http://forum.colemak.com).
There are plenty of explanations and further links in there, as well as links to files.

Happy XKB hacking!
DreymaR, 2018-08

[XKBdat]: https://ubuntu.pkgs.org/18.04/ubuntu-main-amd64/xkb-data_2.23.1-1ubuntu1_all.deb.html (xkb-data download page)
