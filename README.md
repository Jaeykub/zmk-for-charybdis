
# Table of Contents

1.  [Charybdis instructions](#orgd305197)
    1.  [Updating the keymap](#org2e7d8aa)
    2.  [Building the firmware](#org6bb16f8)
    3.  [Flashing the board](#orgf49e282)
    4.  [notes](#org5c38019)


<a id="orgd305197"></a>

# Charybdis instructions


<a id="org2e7d8aa"></a>

## Updating the keymap

The charybdis.keymap file needs to be updated to make changes to the keymap.


<a id="org6bb16f8"></a>

## Building the firmware

A new build is triggered on a commit. Github actions build the firmware and at the bottom there is a firmware download.


<a id="orgf49e282"></a>

## Flashing the board

There will be three files in the firmware folder: \*-right, \*-left, \*settings.
Put a side into bootloader mode (double-click the button underneath), plug in the usb, copy over the \*settings file. Put the side in bootloader mode again and copy over the corresponding side file. Repeat these steps for the other side.
After the board has been flashed the bluetooth connections need to be reset. Clear the profile from the board with the BT<sub>CLEAR</sub> command, and remove the bluetooth connection from the OS.


<a id="org5c38019"></a>

## notes

zmk-config for charybdis (4x6)

