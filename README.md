# Misc Walkthroughs  #

## Internal Links ##

[DWM](https://github.com/luthes/miscdocs#dwm)

[Salt](https://github.com/luthes/miscdocs#salt-stack)

[TerraForm](https://github.com/luthes/miscdocs#terraform)

[AWS CLI](https://github.com/luthes/miscdocs#aws-cli)


## External Links ##

[SaltStack Docs](https://docs.saltstack.com/en/getstarted)

[TerraForm Docs](https://wwww.terraform.io/intro)


Just some stuff that I want to remember. Shortcuts for stuff, walkthroughs, guides, whatever.

## DWM ##

DWM on Ubuntu is fairly easy. Install and compile DWM from source first, then apt-get install. Installing from the Repos after compiling form source sets some config stuff so that I don't have to. Makes life easier.

On my laptop at home, I clond into a suckless folder to keep everything in one spot.

`git clone git://dwm.suckless.org/ suckless/dwm`


[top](https://github.com/luthes/miscdocs#misc-walkthroughs)
### DWM Status ###

Clone from Suckless git repo, and and then use make to install.


`git clone git://dwmstatus.suckless.org/dwmstatus suckless/dwmstatus`

Again, cloning into suckless folder, make from there.


`cd ~/suckless/dwmstatus && sudo make clean install`

And then to start: 

`xsetroot --name "$(dwmstatus)`


[top](https://github.com/luthes/miscdocs#misc-walkthroughs)
### barM.c ###

barM.c is a better config of DWM Status. 

#### Download ####  

`wget http://dwm.suckless.org/dwmstatus/barM.c`

#### Compile ###

`gcc -o barM barM.c -O2 -s -lX11`


#### Run ####

Same as above, run with

`xsetroot -name "$(barM)"`

[top](https://github.com/luthes/miscdocs#misc-walkthroughs)
#### Bash Script to start on Boot ####

Soon (tm).


[top](https://github.com/luthes/miscdocs#misc-walkthroughs)
## Salt Stack ##


[top](https://github.com/luthes/miscdocs#misc-walkthroughs)
## TerraForm ##


[top](https://github.com/luthes/miscdocs#misc-walkthroughs)
## AWS CLI ##


[top](https://github.com/luthes/miscdocs#misc-walkthroughs)


## VIM ##

![VIM Cheat Sheet](https://github.com/luthes/miscdocs/blob/master/vimcheatsheet.png "Cheat Sheet")


Additionally, `vimtutor` should be installed with vim. Just run in a terminal.


[top](https://github.com/luthes/miscdocs#misc-walkthroughs)
## tmux ## 

[tmux Primer by Daniel Miessler](https://danielmiessler.com/study/tmux)

Good tutorial, covers the basics, some helpful hotkey changes as well.





[top](https://github.com/luthes/miscdocs#misc-walkthroughs)

