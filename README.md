#### Suckless Walkthroughs  ####

Just a small tutorial to walk myself through setting up DWM and some addons for it.

test test test

### DWM ###

DWM on Ubuntu is fairly easy. Install and compile DWM from source first, then apt-get install. Installing from the Repos after compiling form source sets some config stuff so that I don't have to. Makes life easier.

On my laptop at home, I clond into a suckless folder to keep everything in one spot.

git clone git://dwm.suckless.org/ suckless/dwm


### DWM Status ###

Clone from Suckless git repo, and and then use make to install.


git clone git://dwmstatus.suckless.org/dwmstatus suckless/dwmstatus

Again, cloning into suckless folder, make from there.


cd ~/suckless/dwmstatus && sudo make clean install

And then to start: 

xsetroot --name "$(dwmstatus) 


### barM.c ###

barM.c is a better config of DWM Status. 

## Download ##  

wget http://dwm.suckless.org/dwmstatus/barM.c

## Compile ##

gcc -o barM barM.c -O2 -s -lX11


## Run ##

Same as above, run with

xsetroot -name "$(barM)"

### Bash Script to start on Boot ###

Soon (tm).
