
# Table of Contents

1.  [Charybdis instructions](#orgcd31c33)
    1.  [Updating the keymap](#org42923b6)
    2.  [Building the firmware](#org4fe0b94)
    3.  [Flashing the board](#org3c81d84)
    4.  [notes](#org491d0d6)


<a id="orgcd31c33"></a>

# Charybdis instructions


<a id="org42923b6"></a>

## Updating the keymap

The charybdis.keymap file needs to be updated to make changes to the keymap.


<a id="org4fe0b94"></a>

## Building the firmware

A new build is triggered on a commit. Github actions build the firmware and at the bottom there is a firmware download.


<a id="org3c81d84"></a>

## Flashing the board

There will be three files in the firmware folder:

-   **-right**
-   **-left**
-   **settings**

Put a side into bootloader mode (double-click the button underneath), plug in the usb, copy over the \*settings file. Put the side in bootloader mode again and copy over the corresponding side file. Repeat these steps for the other side.

After the board has been flashed the bluetooth connections need to be reset. Clear the profile from the board with the *BT\\<sub>CLEAR</sub>* command, and remove the bluetooth connection from the OS.


<a id="org491d0d6"></a>

## notes

zmk-config for charybdis (4x6)

