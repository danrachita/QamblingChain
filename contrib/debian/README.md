
Debian
====================
This directory contains files used to package qamblingchaind/qamblingchain-qt
for Debian-based Linux systems. If you compile qamblingchaind/qamblingchain-qt yourself, there are some useful files here.

## qamblingchain: URI support ##


qamblingchain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install qamblingchain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your qamblingchainqt binary to `/usr/bin`
and the `../../share/pixmaps/qamblingchain128.png` to `/usr/share/pixmaps`

qamblingchain-qt.protocol (KDE)

