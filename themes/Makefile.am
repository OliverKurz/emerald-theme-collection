## Process this file with automake to produce Makefile.in
themesdir = /usr/share/emerald/themes
themes_DATA = \
    Blade.emerald \
    By_Design.emerald \
    Equinox.emerald \
    H2O.emerald \
    H2O_W8.1.emerald \
    HUD_Machine_Red.emerald \
    HUD_Machine_Red_White.emerald \
    Jarvis.emerald \
    Jarvis_Green.emerald \
    Jarvis_Red.emerald \
    Midnight.emerald \
    Midnight_Glass.emerald \
    Nvidia.emerald \
    Poison.emerald \
    Poison_W8.1.emerald \
    Prometheus.emerald \
    Sophistication_Incorporated.emerald \
    Toxic.emerald \
    Toxic_Blue.emerald \
    Toxic_Blue_W8.1.emerald \
    Toxic_W8.1.emerald \
    Windows_10_Black_Edition.emerald \
    Windows_10_Black_Edition_Aqua.emerald \
    Windows_10_Black_Edition_Blue.emerald \
    Windows_10_Black_Edition_Green.emerald \
    Windows_10_Black_Edition_Orange.emerald \
    Windows_10_Black_Edition_Pink.emerald \
    Windows_10_Black_Edition_Red.emerald \
    Zero-G.emerald



EXTRA_DIST = $(themes_DATA) import.sh

#install the .emerald packages properly
install-data-hook:
	$(srcdir)/import.sh "$(DESTDIR)" "$(themesdir)"
