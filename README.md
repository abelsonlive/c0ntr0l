# x0xb0x c0ntr0l software

_adapted from [https://github.com/frak/c0ntr0l](https://github.com/frak/c0ntr0l)_

## How to get it working

1. Install  `.dmg` dependencies in `deps/`

	- These include:

		* The USB/Serial drivers that are correct for your system from the [FTDI website][http://www.ftdichip.com/Drivers/VCP.htm]( most likely 64-bit OS X)

		* The correct version of [the wxWidget libraries](http://sourceforge.net/projects/wxpython/files/wxPython/3.0.0.0/wxPython3.0-osx-3.0.0.0-cocoa-py2.7.dmg/download?use_mirror=iweb) for Mavericks from ( most likely 64-bit OS X)


2. Install additonal requirements:

	brew install wxmac 
	sudo pip install pyserial 

3. Clone this repository

	git clone https://github.com/abelsonlive/c0ntr0l.git

4. Run `c0ntr0l` GUI
	
	cd c0ntr0l/
	python c0ntr0l.py

