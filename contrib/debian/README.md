# Debian

This directory contains files used to package iccd/icc-qt
for Debian-based Linux systems. If you compile iccd/icc-qt yourself, there are some useful files here.

## icc: URI support

icc-qt.desktop (Gnome / Open Desktop)
To install:

    sudo desktop-file-install icc-qt.desktop
    sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your icc-qt binary to `/usr/bin`
and the `../../share/pixmaps/icc128.png` to `/usr/share/pixmaps`

icc-qt.protocol (KDE)
