# Metrology for MusicBee

Metrology is a practical series of customizations and redesigns for bringing a bold, clear, and consistent user experience to various Windows and Android apps. Its design language is based on Metro and Fluent design systems pioneered by Microsoft Design since the 2010s.

[MusicBee](https://musicbee.com) is a highly customizable audiophile-grade music player for Windows. This is a skin for the Theater Mode feature, which displays the currently playing track in a large or full screen format.

There are 4 skins in development:

![Zune](https://i.imgur.com/FXmzjab.png)
Zune: A detailed and accurate replica of the Zune/WP7 Music user interface.

![Fluent Carousel](https://i.imgur.com/woTA1aK.png)
Fluent Carousel: Display the next 10 tracks in a perspective view.

![Fluent](https://i.imgur.com/cVU1DYu.jpg)
Fluent: A bold and clean UI that fits well with Windows 10.

Optionally, an even cleaner version with no controls is available.

## How to Install

### Method A: Install using MusicBee
![Method A Screenshot](https://i.imgur.com/DQd2vOL.png)
Remember to add the XML file as a Theater Mode, not a Skin! Look for the right menu item marked under View > Theater Mode. If you do the latter, your MusicBee will crash hard.

### Method B: Install by copying files in Explorer
![Method B Screenshot](https://i.imgur.com/nJtZ6S1.png)
Find the folder where you installed MusicBee, which is usually under C:\Program Files (x86)\MusicBee\. Go to the Plugins folder and you will find two TheaterMode folders.

If you want to use the Theater Mode in a tab in the main window as a Now Playing view, or if you want to use it in Compact View, copy the xml file to TheaterMode.Embeded.

If you want to use the Theater Mode as a full screen window or its own window, copy the xml file to TheaterMode.List.

## System Requirements
* MusicBee 3.x
* Windows 10 with the Segoe MDL2 Assets font. Without it all the icons won't work. If you aren't on Windows 10 1903 or later, download the font here: https://aka.ms/SegoeFonts

## Credits
Please feel free to redistribute and the only thing I ask is to give proper credits back to me. That would help my livelihood since design is [my career](https://MadelenaMak.com).

The initial code was partially based on the Rdio Theater Mode view.
