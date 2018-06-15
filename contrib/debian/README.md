
Debian
====================
This directory contains files used to package shadowd/shadow-qt
for Debian-based Linux systems. If you compile shadowd/shadow-qt yourself, there are some useful files here.

## shadow: URI support ##


shadow-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install shadow-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your shadowqt binary to `/usr/bin`
and the `../../share/pixmaps/shadow128.png` to `/usr/share/pixmaps`

shadow-qt.protocol (KDE)

