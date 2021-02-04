# mc-161816 (Pre-Classic)
Development phase: May 16, 2009 (until 18:16 UTC+2)

## Unofficial name
While this version is known to exist it is missing from the launcher and has not been archived elsewhere, meaning that it is currently lost.<br>
<br>
The version name is taken from [Notchs IRC message](https://archive.org/download/Minecraft_IRC_Logs_2009/history/files/May-15-to-June-03-2009/2009-05-16.075419-0400EDT.txt.~1~) <br>
``(12:16:34) notch: dock, fartron: There's a new version up. Reload the page``
<br>
<br>
Minecraft Wiki uses ``mc-161616`` for this version because it's in UTC format.
``mc-161816`` would be in UTC+2 (Timezone in Sweden)

## Changes
- Added Y hotkey: Swap mouse input on Y axis 
- Calculate mouse motion in applet mode

## Accuracy
This version has only been sent to [dock](https://minecraft.gamepedia.com/Hayden_Scott-Baron) and [fartron](https://forums.tigsource.com/index.php?action=profile;u=61) for testing.
There is no existing backup.
The changes were taken from future versions based on the IRC logs.

## References
- [Minecraft Wiki - Java_Edition_pre-Classic_mc-161616](https://minecraft.gamepedia.com/Java_Edition_pre-Classic_mc-161616)
- [IRC logs](https://archive.org/download/Minecraft_IRC_Logs_2009/history/files/May-15-to-June-03-2009/2009-05-16.075419-0400EDT.txt.~1~)  to recreate the unreleased features:
    - ``[12:16:34] notch: dock, fartron: There's a new version up. Reload the page``
    - ``[12:16:40] notch: 'Y' swaps the y axis on the mouse``
    - ``[12:16:48] notch: and the mouse look code is changed``

## Setup
1. Clone the project
2. Set the VM option ``-Dorg.lwjgl.librarypath="<path_to_project>/run/natives"``
3. Set the working directory to ``./run``