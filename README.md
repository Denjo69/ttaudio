# tta - TipToi Audio

tta converts a collection of *.mp3 or *.ogg audio files into a single *.gme file to play  on the [Ravensburger TipToi](https://www.ravensburger.de/shop/tiptoi/index.html) pen.

## Workflow
* Attach the TipToi stick to the USB port of your computer
* Start tta.exe
* Drop audio files into the file list
* Click "Convert"
* Wait until tta has transcoded the audio files
* A web page showing the contained albums pops up
* Print the web page
* Wait until ttab has copied the *.gme file to the stick

## Dependencies

Internally, tta uses following tools
* [mpg123-1.22.0-x86-64](http://www.mpg123.de/download.shtml) to decode mp3 files
* [oggenc2.exe](http://www.rarewares.org/ogg-oggenc.php) to encode the ogg files for the TipToi stick
* [oggdec.exe](http://www.rarewares.org/ogg-oggdec.php) to decode input *.ogg files
* [tttool-win32-1.5.1](https://github.com/entropia/tip-toi-reveng) to assemble the *.gme files

