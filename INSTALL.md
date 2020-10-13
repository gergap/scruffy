# Install

Scruffy requires dependencies which can be tricky to install.
Here's a way to install them easily.

## OSX

	# dependencies
	brew install graphviz plotutils
	brew install imagemagick --with-librsvg

	# if you haven't `pip` yet
	curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
	sudo python get-pip.py

	# install `scuffy` and `image` (PIL replacement)
	sudo pip install image scruffy

Tested on OSX 10.10.5

## Debian Linux

### Install Fonts

* Dekko Font: This is used by yuml.me
  Download from https://fonts.google.com/specimen/Dekko
* Purisa Font: This is used originally by scruffiy
  `sudo apt install fonts-tlwg-purisa-ttf`

### Dependencies

```
sudo apt install graphviz plotutils python3-scruffy librsvg2-bin imagemagick
```
