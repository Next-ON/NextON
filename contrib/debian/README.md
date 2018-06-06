
Debian
====================
This directory contains files used to package nxtond/nxton-qt
for Debian-based Linux systems. If you compile nxtond/nxton-qt yourself, there are some useful files here.

## nxton: URI support ##


nxton-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nxton-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nxtonqt binary to `/usr/bin`
and the `../../share/pixmaps/nxton128.png` to `/usr/share/pixmaps`

nxton-qt.protocol (KDE)

