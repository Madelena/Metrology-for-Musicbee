# Metrology for MusicBee

Metrology is a practical series of app customizations and redesigns aimed at bringing a bold, clear, and consistent user experience to various Windows and Android apps. Its design language is based on [Metro](https://en.wikipedia.org/wiki/Metro_(design_language)) and [Fluent](https://www.microsoft.com/design/fluent/) design systems pioneered by Microsoft Design since the 2010s.

[MusicBee](https://getmusicbee.com) is a highly customizable audiophile-grade music player for Windows. This is a skin for the Theater Mode, which displays the currently playing track in a large or full screen format.

## Table of Contents

- [Skins](#skins)
- [How to Install](#how-to-install)
- [How to Load](#how-to-load)
- [How to Use](#how-to-use)
- [System Requirements](#system-requirements)
- [Credits](#credits)

## Skins
There are 5 skins in development:

**Zune**: A detailed and accurate replica of the Zune/WP7 Music user interface.

<img src="https://i.imgur.com/FXmzjab.png" width="75%" alt="Zune"/>

**Fluent Carousel**: A striking perspective view for showing the next 10 tracks.

<img alt="Fluent Carousel" src="https://i.imgur.com/woTA1aK.png" width="75%"/>

**Fluent**: A bold and clean UI that fits well with Windows 10. Optionally, a 4K fullscreen version is available.

<img alt="Fluent" src="https://i.imgur.com/XbH7R0T.png" width="75%"/>

**Fluent Wall**: A beautiful display of the next dozens of tracks on a grid backdrop.

<img alt="Fluent Wall" src="https://i.imgur.com/9cv1bGp.png" width="75%"/>

## How to Install

1. Download the latest release here: https://github.com/Madelena/Metrology-for-Musicbee/releases 
2. Extract the zip file and you will find a bunch of xml files. Each xml file is a Theater Mode skin.
3. Go to C:\Program Files (x86)\MusicBee\Plugins or where you installed MusicBee. In the Plugins folder, you will find two TheaterMode folders.
4. Copy the xml files to TheaterMode.Embeded, if you want to use the Theater Mode in the Now Playing tab or in the Compact View window, 
5. Copy the xml files to TheaterMode.List, if you want to use the Theater Mode as a full screen window or its own window.

The end result should look something like this:

<img alt="Method B Screenshot" src="https://i.imgur.com/nJtZ6S1.png" width="50%"/>

**IMPORTANT**: Remember to add the XML file as a Theater Mode Skin, not a normal Skin! Look for the right folder! If you make the mistake of installing as a normal Skin under the Skins folder, your MusicBee will *crash hard*.

## How to Load

If you're a first-timer on MusicBee, you will realize that the app can be difficult to learn initially, mainly because its navigation methods are quite old school and rather different from contemporary music players such as Spotify. However, once you get a hang of it, you can customize it exactly to your liking.

There are 3 ways to use Theater Mode on MusicBee.

### Use Case 1: Use on the Now Playing tab
The Now Playing tab fills the entire window with information about the now playing track. By default, the Now Playing tab should be visible. You can switch the view to Metrology with the header menu hidden at the top left on the text that says "Now Playing":

<img alt="Now Playing tab" src="https://i.imgur.com/DSb9KSV.png" width="50%"/>

### Use Case 2: Use as a Full Screen visual
You can fill the entire screen up with Metrology, by selecting it on the View > Theater Mode menu:

<img alt="Theater Mode menu" src="https://i.imgur.com/lfinLHX.png" width="50%"/>

### Use Case 3: Use on the Compact Player window
The Compact Player view floats the music player in a small window. You can access Compact Player from the View menu:

<img alt="Compact Player Step 1" src="https://i.imgur.com/V0UiiNd.png" width="50%"/>

And then switch to Metrology with the main menu on the Compact Player window:

<img alt="Compact Player Step 2" src="https://i.imgur.com/1xwpEhS.png" width="50%"/>

To exit Compact Player, click Maximize (the square button) at the top right of the window.

## How to Use
In a few skins, the player controls are hidden from view for aesthetics. To reveal them, move your cursor over the bottom right area where the UP NEXT track description is:

<img alt="Reveal player controls" src="https://i.imgur.com/oR8otdL.gif" width="50%"/>

The buttons are pretty straightforward. Here's what they do from left to right:

<img alt="Player Controls" src="https://i.imgur.com/BnlG9RC.png" width="50%"/>

- Previous Track button
- Play / Pause button
- Next Track button
- Search button: Opens up the "Now Playing Assistant", which allows you to search for a different track to play quickly.
- More button: Reveals the music queue, lyrics, and artist biography.

In some Fluent skins, the album cover can be resized to reveal a larger album cover more player controls (Progress Bar, Last.fm Love button, Shuffle and Repeat buttons):

<img alt="Resize Button" src="https://i.imgur.com/FSz2rsJ.gif" width="50%"/>

## System Requirements
* MusicBee 3.x
* Windows 10 with the Segoe MDL2 Assets font. Without it all the icons won't work. If you aren't on Windows 10 1903 or later, download the font here: https://aka.ms/SegoeFonts
* 1080p screen resolution minimum, and the special 4K version needs a 4K screen.

## Credits

![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

Additionally, I would appreciate proper credits back to me if redistributed or modified. That would help my livelihood since design is [my career](https://MadelenaMak.com).

The initial code was partially based on the Rdio Theater Mode view.
