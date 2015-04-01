# fuzify
Strips unnecessary metadata from mp3/ogg files (optimized for Sansa Fuze)

Sansa Fuze players have a tendency to take quite a while to index metadata any time something changes in the memory or on a Micro SD card. This script removes unnecessary tags and converts tags to the format preferred by the Fuze.

The script traverses a directory tree and strips unnecessary tags from mp3 and ogg files (could easily be extended to FLAC). Leaves, basically, name, artist, track title, track number, and a few other things.

It also strips image tags and writes folder.jpg files instead.

Recommended usage: copy all the music from your micro SD card to your hard drive, format the SD card (preferably using SD Formatter, https://www.sdcard.org/downloads/formatter_4/) run this script on the music folder on your hard drive, and then copy it back.

Do the same for the internal memory. But, it's best to format the internal memory using the built-in format function on the Fuze.

This should work for other Sansa players as well (Clip etc) but it has not been tested on them.


