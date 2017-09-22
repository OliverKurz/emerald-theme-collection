Emerald Theme Collection
========================
This is a complete collection of my premium theme ports for the Emerald Compiz Window Decorator. Compatible Desktop Environments: Any Desktop Environment which can run Compiz.

![Emerald_Theme_Collection](https://github.com/OliverKurz/emerald-theme-collection/raw/master/images/Preview.png)

Installation Walkthrough
------------------------
1. Install a Linux distribution that supports a Desktop Environment which Compiz can be run on.

2. Install Compiz and Emerald (I recommend checking out the Compiz Reloaded project).

3. cd into the directory this archive is cloned or copied into and type the following commands:

```
$ ./autogen.sh
$ make
$ sudo make install
```

4. Cut/paste the fonts included in the "fonts" directory to the correct fonts directory (usually "/usr/share/fonts/truetype").

5. Run Compiz and run Emerald as the Window Decoration.

6. Open the Emerald Theme Manager and there should be system themes with the tag _Emerald in their title. I recommend unchecking all of the options in the Emerald Settings section in the Emerald Theme Manager, as well as disabling the button fade and pulse settings. Uninstalling these Emerald themes for now can be done by cding as administrator into the /usr/share/emerald/thenes directory and searching for folders to delete with the tag _Emerald.

Known Issues
------------
1. Emerald themes do not uninstall using `sudo make uninstall`.

2. Installing fonts is an annoying manual extra step.

Credits
--------
Original theme designs by Mr GRiM, Razorsedge, gsw953, and Tornado. Visit [Virtual Customs](http://virtualcustoms.net/forum.php) for more.

Thanks to the [Compiz Reloaded](https://github.com/compiz-reloaded) team.