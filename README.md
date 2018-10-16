# gpdp2-bunsenlabs-respin
My ~/.config on a GPD Pocket 2 running Bunsenlabs. This lisnux distro is realy impressive and totaly fit the GPDP2.
Fast to start, lightweight, based on a debian so all the packages on debian's repository are available.
It's works way better than Ubuntu for me.
Give it a try.

Just install Bunsenlabs from there https://www.bunsenlabs.org/ and copy all de replace the files in your .config directory by mine.

You can change the scale(DPI) with CTRL + ALT + 0-4 : 1=normal scale; 2=0.8x; 3=0.6x; 4=0.4x.
Openbox start with a scale of 0.4x
The keybinds are in config/openbox/rc.xml between the <keyboard><\keyboard>.

The three commands used to correctly setup the screen at startup are in .config/openbox/autostart.
These are :
xrandr -o right &
xrandr --output eDP-1 --scale 0.4x0.4 &
xinput set-prop 12 142 0 1 0 -1 0 1 0 0 1 &

Don't forget the "&" at the end otherwise it'll dosesn't work.

That's about it.

Things to work on : 
Too many :)
