## Lumia535Utils
Bunch of tools used for the Lumia 535

# How to use
## Download the files
Download the files from the Releases tab, choose which EFIESP you want: Devmenu only is just to unlock, the EDK2 one is for booting Linux and such.

## Flashing the modified EFIESP
Open Windows Phone Internals, either from the downloaded .zip, or from the [official WPinternals GitHub](https://github.com/ReneLergner/WPinternals).
Go to the Flash section under Platform.
Scroll down to "Flash separate partitions", and select the EFIESP file to flash.

## Booting into Mass Storage mode
After flashing, WPinternals will reboot the phone, hold down the Volume down key to get into Developer Menu.
When in Developer Menu you will see a few options, the one that interests us is the Boot into mass storage option, so press the power button, and you're there.

## Unlocking
Close any WPinternals window, and open the Unlock.bat, while being in mass storage mode.

## Booting into EDK2
If you've flashed the EFIESP with EDK2, just restart your phone, and press the Volume Up button.

