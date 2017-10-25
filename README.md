# Dutch Radio skill

This skill streams radio from urls. It uses vlc so you have to install that with:
sudo apt-get install vlc

I changed mpg123 to vlc because it seems to hang less on raspberry pi.
Change the csv to add or change channels in to your own language.

Add or change urls with streams you like from http://www.hendrikjansen.nl/henk/streaming.html

It is based upon https://github.com/forslund/mycroft-media-skills/tree/master/swedishradio

## Current state

Working features:
 - turn on 3fm
 - stream radio 1
 - play radio arrow classic rock

Known issues:
 - none, so far

TODO:
 - Add volume adjustment when using wakeword.
