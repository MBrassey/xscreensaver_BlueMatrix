# xscreensaver_BlueMatrix

xscreensaver with Blue XMatrix and GLMatrix Screensavers:
<br />
![XMatrix_Screensaver](XMatrix.png)
<br />
![GLMatrix_Screensaver](GLMatrix.png)

#### Prepare your system
Uninstall xscreensaver if you have it installed:

    sudo apt remove xscreensaver

Add sourcecode files needed to make the project:
<br />

    Dash > Software & Updates > Ubuntu Software > Check Source Code Box

Install dependencies needed for compilation:
<br />

    sudo apt build-dep xscreensaver

#### Compile from Source
<br />
Download the sourcecode:

    git clone https://github.com/luc1dLife/xscreensaver_BlueMatrix.git

<br />

    cd to xscreensaver_BlueMatrix\
    ./configure
    sudo make
    sudo make install clean    # disregard any errors
    sudo make install

<br />

Start xscreensaver:

    Dash > screensaver    # navigate to GLMatrix or XMatrix

<br />
GLMatrix & XMatrix are now updated with Blue symbols instead of Green. I'm currently unaware of a better blue colored matrix screensaver for linux. 
