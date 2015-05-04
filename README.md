# PiPlayer
Web front end for a Raspberry Pi music player

Currently in beta test in my home.

Hardware
CanaKit from Amazon
- Raspberry PI Model B+
- 8 GB SD card with NOOBS
- WiFi Dongle
- Case
- Power supply
Perteilan LCD display - unfortunately no longer made.  It was a nice little display.  I had 2 sitting around, so I put one to good use.
Griffin PowerMate USB Media Controller - Basically a big silver knob that you can turn and press like a button.
Logitech Speaker System - Sort of like the Z313 but older.  I have 3 of these sitting around, so I used one.
A small USB hard drive for the music.

Software
Raspian
mpd music player daemon
LCDroc to manage the Perteilan
lighttpd web server
Python
- jinglemansweep/lcdproc - to talk to LCDProc
- bethebunny/powermate - to listen to the PowerMate
