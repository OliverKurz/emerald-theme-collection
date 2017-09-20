## Process this file with automake to produce Makefile.in
themesdir = /usr/share/emerald/themes
themes_DATA = \
    Annihilator_Emerald.emerald \
    Blade_Emerald.emerald \
    By_Design_Emerald.emerald \
    Castle_Emerald.emerald \
    Chrononaut_Emerald.emerald \
    Consolidated_Emerald.emerald \
    DeathStar_Emerald.emerald \
    DeathStar_Blue_Emerald.emerald \
    Equinox_Emerald.emerald \
    Friday_the_13th_Emerald.emerald \
    H2O_Emerald.emerald \
    H2O_v2_Emerald.emerald \
    HUD_Machine_Red_Emerald.emerald \
    HUD_Machine_Red_White_Emerald.emerald \
    Jarvis_Emerald.emerald \
    John_Wick_Emerald.emerald \
    Maximum_Security_One_Emerald.emerald \
    Maximum_Security_One_Green_Emerald.emerald \
    Metal_Graveyard_Emerald.emerald \
    Midnight_Emerald.emerald \
    Midnight_Glass_Emerald.emerald \
    Nightshade_Emerald.emerald \
    Nvidia_Emerald.emerald \
    Poison_Emerald.emerald \
    Poison_v2_Emerald.emerald \
    Prometheus_Emerald.emerald \
    Prometheus_Ghost_Emerald.emerald \
    Prometheus_Green_Emerald.emerald \
    Prometheus_Orange_Emerald.emerald \
    Prometheus_Revisioned_Emerald.emerald \
    Retribution_Emerald.emerald \
    Sophistication_Incorporated_Emerald.emerald \
    Toxic_Blue_Emerald.emerald \
    Toxic_Blue_v2_Emerald.emerald \
    Toxic_Emerald.emerald \
    Toxic_v2_Emerald.emerald \
    Windows_10_Black_Edition_Aqua_Emerald.emerald \
    Windows_10_Black_Edition_Blue_Emerald.emerald \
    Windows_10_Black_Edition_Emerald.emerald \
    Windows_10_Black_Edition_Green_Emerald.emerald \
    Windows_10_Black_Edition_Orange_Emerald.emerald \
    Windows_10_Black_Edition_Pink_Emerald.emerald \
    Windows_10_Black_Edition_Red_Emerald.emerald \
    Zero-G_Emerald.emerald

EXTRA_DIST = $(themes_DATA) import.sh

#install the .emerald packages properly
install-data-hook:
	$(srcdir)/import.sh "$(DESTDIR)" "$(themesdir)"
