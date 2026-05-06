* Charybdis instructions
** Updating the keymap
The charybdis.keymap file needs to be updated to make changes to the keymap.
** Building the firmware
A new build is triggered on a commit. Github actions build the firmware and at the bottom there is a firmware download.
** Flashing the board
There will be three files in the firmware folder: *-right, *-left, *settings.
Put a side into bootloader mode (double-click the button underneath), plug in the usb, copy over the *settings file. Put the side in bootloader mode again and copy over the corresponding side file. Repeat these steps for the other side.

** notes
zmk-config for charybdis (4x6)
