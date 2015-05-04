# PiPlayer
Raspberry Pi music player

Currently in beta test in my home.

I have 2 players right now:
1. The main one in the living room which has the Pertelian and Powermate connected to it - and a web interface.
2. The bed room one which has only the web interface.  I use my tablet (which I keep on my nightstand) to control it.

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
