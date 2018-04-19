
Debian
====================
This directory contains files used to package nitropayd/nitropay-qt
for Debian-based Linux systems. If you compile nitropayd/nitropay-qt yourself, there are some useful files here.

## nitropay: URI support ##


nitropay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nitropay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nitropay-qt binary to `/usr/bin`
and the `../../share/pixmaps/nitropay128.png` to `/usr/share/pixmaps`

nitropay-qt.protocol (KDE)

