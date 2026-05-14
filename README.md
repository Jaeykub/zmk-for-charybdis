
# Table of Contents

1.  [Charybdis instructions](#orga091b20)
    1.  [Updating the keymap](#orgdfbcec1)
    2.  [Building the firmware](#org3e0f1c1)
    3.  [Flashing the board](#org5791711)
    4.  [notes](#org7997be0)


<a id="orga091b20"></a>

# Charybdis instructions


<a id="orgdfbcec1"></a>

## Updating the keymap

The charybdis.keymap file needs to be updated to make changes to the keymap.


<a id="org3e0f1c1"></a>

## Building the firmware

A new build is triggered on a commit. Github actions build the firmware and at the bottom there is a firmware download.


<a id="org5791711"></a>

## Flashing the board

There will be three files in the firmware folder: \*-right, \*-left, \*settings.
Put a side into bootloader mode (double-click the button underneath), plug in the usb, copy over the \*settings file. Put the side in bootloader mode again and copy over the corresponding side file. Repeat these steps for the other side.

After the board has been flashed the bluetooth connections need to be reset. Clear the profile from the board with the *BT<sub>CLEAR</sub>* command, and remove the bluetooth connection from the OS.


<a id="org7997be0"></a>

## notes

zmk-config for charybdis (4x6)

