# x0xb0x c0ntr0l software #
As the c0ntr0l software appears to be abandonware, here is an updated
version of the code that I found on [Sourceforge][sf]. Nothing has been
changed functionality wise, but I need to clean up some `true`'s, `NULL`'s
and import the wx widget library correctly.

## How to get it working ##
These instructions are slightly adapted from those found on the 
[Adafruit forums][ada].  As I am on a Mac, I had no need to install Python
as 2.7 is already avaiilable to me. I then installed the [correct version][vcp]
of the wxWidget libraries for Mavericks, and extracted the [pyserial][pys]
library and after extracting them I ran `python setup.py install`.  After this
I installed the USB/Serial drivers that were correct for my system (64-bit OS X)
from the [FTDI website][ftdi].  After this, things got harder as the source
code for c0ntr0l was very hard to find.  However, you have found this repository
and your search is over.  Connect your x0xb0x, run python c0ntr0l.py and you
should be good to go.

## Things to fix ##
The play pattern button doesn't seem to work at present, I will take a
look into that at some stage as I want it working for myself...

[sf]: http://x0xb0x.cvs.sourceforge.net/viewvc/x0xb0x/
[ada]: https://forums.adafruit.com/viewtopic.php?f=13&t=11620&start=11
[vcp]: http://downloads.sourceforge.net/wxpython/wxPython3.0-osx-3.0.0.0-cocoa-py2.7.dmg
[ftdi]: http://www.ftdichip.com/Drivers/VCP.htm