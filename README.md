# NewMusicProject
NewMusicProject (will be renamed) -  a new music player for Windows 10

## Features

* Play music in your music library
* Read lyrics for currently-playing music (limited)
* Import iTunes playlists
* Last.fm scrobbling

## Supported OS Versions/Devices:

* Windows 10 Build 19041+ (running an Insider build may result in unexpected behavior) x86/64 and ARM (I've compiled it for ARM/ARM64 so it should work with Surface Pro X devices.)

## Bugs

This is the very first beta; so there are a few bugs:

* If you are using a High-Contrast theme the app will fail at startup. I will provide a fix in the next beta.
* Pressing F1 displays an empty Grid. will be addressed in later beta.
* Windows 10X has an issue with thumbnails so it won't display song/album thumbnails.
* the "Add To" button in the Albums page does not do anything.
* some layout issues need to be fixed.
* The app only checks for new music at startup and if the "Refresh Library" button is pressed in the More menu on the sidebar. This is due to limitations in the Windows.Storage APIs. Also the app cant track files that have been delleted.
* The Shuffle button in the player controls doesn't work.
* Music sometimes does not play automatically. Press the Play/Pause button to start playing the music.

(if there are any other bugs in this app, raise an issue on this page.)
