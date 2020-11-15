# Mustastic
Mustastic -  a new music player for Windows 10

![Home page](https://github.com/TyJOrtiz/NewMusicProject/blob/main/Screenshots/Screenshot%20(43).png?raw=true)

![album view](https://github.com/TyJOrtiz/NewMusicProject/blob/main/Screenshots/Screenshot%20(45).png?raw=true)

![compact view](https://github.com/TyJOrtiz/NewMusicProject/blob/main/Screenshots/Screenshot%20(46).png?raw=true)

![now playing view](https://github.com/TyJOrtiz/NewMusicProject/blob/main/Screenshots/Screenshot%20(47).png?raw=true)

## Features

* Play music in your music library
* Read lyrics for currently-playing music (limited)
* Import iTunes playlists
* Last.fm scrobbling

## Supported OS Versions/Devices:

* Windows 10 Build 19041+ (running an Insider build may result in unexpected behavior) x86/64 and ARM (I've compiled it for ARM/ARM64 so it should work with Surface Pro X devices.)

## Bugs

* Accessibilty features are very much lacking. Will be addressed in future betas.
* Pressing F1 displays an empty Grid. will be addressed in later beta.
* Windows 10X has an issue with thumbnails so it won't display song/album thumbnails.
* some layout issues need to be fixed.
* The app only checks for new music at startup and if the "Refresh Library" button is pressed in the More menu on the sidebar. This is due to limitations in the Windows.Storage APIs. Also the app cant track files that have been delleted.
* Music sometimes does not play automatically. Press the Play/Pause button to start playing the music.

## Roadmap

* Screen reader features
* Shuffle playback list
* Lyrics support

(if there are any other bugs in this app, raise an issue on this page. or email [me](tyler.j.ortiz@outlook.com)
