# xscreensaver_BlueMatrix
xscreensaver with Blue XMatrix and GLMatrix Screensavers

#### Preparation
Uninstall xscreensaver if you have it installed:

    sudo apt remove xscreensaver

Add sourcecode files needed to make the project:
<br />
Dash > Software & Updates > Ubuntu Software > Check Source Code Box

#### Compile from Source
Prepare your sysrem:

    sudo apt-get build-dep xscreensaver

<br />
Download the sourcecode:

    git clone https://github.com/luc1dLife/xscreensaver_BlueMatrix.git\

<br />

    cd to xscreensaver_BlueMatrix\
    ./configure
    sudo make
    sudo make install
    sudo make install clean

<br />

Start xscreensaver:
    Dash > screensaver

<br />

GLMatrix & XMatrix are now Blue instead of Green. Untill this option is added officially, compiling this source is the best option i've found for BlueMarix. 

