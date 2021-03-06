Emerald Theme Collection
========================
This is a complete collection of premium themes for the Emerald Compiz Window Decorator.

![Emerald_Theme_Collection](https://github.com/OliverKurz/emerald-theme-collection/raw/master/images/Preview.png)

Installation Walkthrough
------------------------
1. Choose a Linux distribution that supports MATE, Xfce, LXDE, or LXQt.

2. Install Compiz and Emerald. The [Compiz Reloaded project](https://github.com/compiz-reloaded) is recommended.

3. `cd` into the directory the archive was cloned or copied to and enter the commands:

```
$ ./autogen.sh
$ make
$ sudo make install
```

4. Cut/paste the fonts from `/fonts` into `/usr/share/fonts/truetype`.

5. Start Compiz, and run Emerald for the Window Decoration.

6. Start Emerald Theme Manager. In the Emerald Settings tab try unchecking all of the options and disabling button fade and pulse for the best theme performance.

* Uninstalling the Emerald themes can be achieved by `cd`ing as admin into `/usr/share/emerald/themes` and searching for folders to delete with the name _Emerald.

Known Issues
------------
1. Emerald themes don't uninstall using `sudo make uninstall`.

2. Installing fonts is an extra step that should be automated.

Credits
--------
Original theme designs by Mr GRiM, Razorsedge, gsw953, and Tornado. Visit [Virtual Customs](http://virtualcustoms.net/forum.php) for more.

[Compiz Reloaded](https://github.com/compiz-reloaded).
