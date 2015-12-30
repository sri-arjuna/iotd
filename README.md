IotD - NASA
===========

Image of the Day from NASA as your wallpaper!


Requires:
---------
* Bash
* feh 
* ImageMagick (optional, if you want to automaticly 'resize' the downloaded images to your screen res)

Also, but nothing to worry about:
* TUI (will be installed automaticly if missing)


Install:
--------

1. Bash first
2. change to the downloaded path of nasa-iotd.
3. Install it

	./configure --prefix=/usr
	
	./make
	
	sudo ./make-install
	
	\#sudo ./make-uninstall

Execute / Run it:
-----------------
Open a terminal and call either:

	iotd
	changebg

Configure it:
-----------------

	tui-edit ~/.iotd
