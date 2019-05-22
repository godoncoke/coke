
Debian
====================
This directory contains files used to package idoprofitidocoked/idoprofitidocoke-qt
for Debian-based Linux systems. If you compile idoprofitidocoked/idoprofitidocoke-qt yourself, there are some useful files here.

## idoprofitidocoke: URI support ##


idoprofitidocoke-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install idoprofitidocoke-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your idoprofitidocoke-qt binary to `/usr/bin`
and the `../../share/pixmaps/idoprofitidocoke128.png` to `/usr/share/pixmaps`

idoprofitidocoke-qt.protocol (KDE)

