
# Table of Contents

1.  [Charybdis instructions](#org9b769af)
    1.  [Updating the keymap](#org3821a2c)
    2.  [Building the firmware](#orge7eec41)
    3.  [Flashing the board](#org3665466)
    4.  [notes](#org53a13a7)


<a id="org9b769af"></a>

# Charybdis instructions


<a id="org3821a2c"></a>

## Updating the keymap

The charybdis.keymap file needs to be updated to make changes to the keymap.


<a id="orge7eec41"></a>

## Building the firmware

A new build is triggered on a commit. Github actions build the firmware and at the bottom there is a firmware download.


<a id="org3665466"></a>

## Flashing the board

There will be three files in the firmware folder: \*-right, \*-left, \*settings.
Put a side into bootloader mode (double-click the button underneath), plug in the usb, copy over the \*settings file. Put the side in bootloader mode again and copy over the corresponding side file. Repeat these steps for the other side.


<a id="org53a13a7"></a>

## notes

zmk-config for charybdis (4x6)

