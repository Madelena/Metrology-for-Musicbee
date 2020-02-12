# Metrology for MusicBee

Metrology is a practical series of app customizations and redesigns aimed at bringing a bold, clear, and consistent user experience to various Windows and Android apps. Its design language is based on [Metro](https://en.wikipedia.org/wiki/Metro_(design_language)) and [Fluent](https://www.microsoft.com/design/fluent/) design systems pioneered by Microsoft Design since the 2010s.

[MusicBee](https://getmusicbee.com) is a highly customizable audiophile-grade music player for Windows. This is a skin for the Theater Mode, which displays the currently playing track in a large or full screen format.

## Table of Contents

- [Skins](#skins)
- [How to Install](#how-to-install)
- [How to Use](#how-to-use)
- [System Requirements](#system-requirements)
- [Credits](#credits)

## Skins
There are 5 skins in development:

![Zune](https://i.imgur.com/FXmzjab.png)
**Zune**: A detailed and accurate replica of the Zune/WP7 Music user interface.

![Fluent Carousel](https://i.imgur.com/woTA1aK.png)
**Fluent Carousel**: Display the next 10 tracks in a perspective view.

![Fluent](https://i.imgur.com/cVU1DYu.jpg)
**Fluent**: A bold and clean UI that fits well with Windows 10.

Optionally, a 4K fullscreen version is available.

![Fluent Wall](https://i.imgur.com/9cv1bGp.png)
**Fluent Wall**: Display the next 28 tracks on a grid backdrop in a randomized order.

## How to Install

1. Download the latest release here: https://github.com/Madelena/Metrology-for-Musicbee/releases 
2. Extract the zip file and you will find a bunch of xml files. Each xml file is a Theater Mode skin.
3. Go to C:\Program Files (x86)\MusicBee\Plugins or where you installed MusicBee. In the Plugins folder, you will find two TheaterMode folders.
4. Copy the xml files to TheaterMode.Embeded, if you want to use the Theater Mode in the Now Playing tab or in the Compact View window, 
5. Copy the xml files to TheaterMode.List, if you want to use the Theater Mode as a full screen window or its own window.

The end result should look something like this:
![Method B Screenshot](https://i.imgur.com/nJtZ6S1.png)

**IMPORTANT**: Remember to add the XML file as a Theater Mode Skin, not a normal Skin! Look for the right menu item marked under View > Theater Mode. If you make the mistake of installing as a normal Skin, your MusicBee will *crash hard*.

## How to Use

There are 3 ways to use Theater Mode on MusicBee.

### Use Case 1: Use on the Now Playing tab

### Use Case 2: Use as a Full Screen visual

### Use Case 3: Use on the Compact View window


## System Requirements
* MusicBee 3.x
* Windows 10 with the Segoe MDL2 Assets font. Without it all the icons won't work. If you aren't on Windows 10 1903 or later, download the font here: https://aka.ms/SegoeFonts
* 1080p screen resolution minimum, and the special 4K version needs a 4K screen.

## Credits

![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

Additionally, I would appreciate proper credits back to me if redistributed or modified. That would help my livelihood since design is [my career](https://MadelenaMak.com).

The initial code was partially based on the Rdio Theater Mode view.
