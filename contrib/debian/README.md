
Debian
====================
This directory contains files used to package hiredcoind/hiredcoin-qt
for Debian-based Linux systems. If you compile hiredcoind/hiredcoin-qt yourself, there are some useful files here.

## hiredcoin: URI support ##


hiredcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hiredcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hiredcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/hiredcoin128.png` to `/usr/share/pixmaps`

hiredcoin-qt.protocol (KDE)

