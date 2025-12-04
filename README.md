# CGA dotfiles
these are some dotfiles for a 640x200 setup

This setup uses tint2, pcmanfm, l3afpad, and jgmenu primarily to provide a compact interface, maximizing screen space and even allowing for multitasking.

Some things to note about this setup:
* The GTK theme might be a little bit strange
* Icons are not super consistent
* You may have to move oversize windows by right clicking on their titlebar, selecting move, and using the arrow keys
* Color and shades of gray are missing making some things extremely hard to read

For most of this, just copy this repo into your home directory and change the names of the folders config, fonts, icons, and themes to .config, .fonts, .icons, and .themes . Some components are separate from this repo. Download the following separately:
* Cursor theme (coming soon)
* GTK hicolor icon theme:
  * Install the hicolor icon theme
  * Go to /usr/share/themes/ and copy it into ~/.icons
  * Copy and paste everything from the 1bit folder into the hicolor theme (replacing files)
  * rename the hicolor folder to 1bit
* tint2, openbox (to disable hinting compile), jgmenu, pcmanfm-gtk3 using a package manager

I would recommend compiling openbox without minimum window hinting, especially if you have to deal with the awful GTK file select dialog frequently.
