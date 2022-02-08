# Lilygo watch builder

This is a modified script for the lilygo watch 
it is like the AtcWatch builder for a different watch 

run 
setuplilygo newdir
it creates nedir contaning all that is needed 
including scripts
scripts should be run script PROGECTNAME to attaxch build or upload
setenv should be sourced if you want to work in bash 
note it changes your HOME so ou might want to run in a subsehll
  attach  
  build        
  setenv 
  upload


and it donwlaods all that is needed
see below for comments 
this is a work in progress not compleate but it can build and upload from command line 


I started playing with one of these
http://www.lilygo.cn/prod_view.aspx?TypeId=50053&Id=1290&FId=t3:50053:3

I bought form https://usa.banggood.com/ for around $43 in late December it arrived early February in New York prices are all over the plase if you look for it so shop around if you want you also might want to consider paying more for faster delivery

setup is described nicely here
http://www.lilygo.cn/prod_view.aspx?TypeId=50053&Id=1290&FId=t3:50053:3

I got the LILYGO T-WATCH-2020 V2 because I wanted the GPS
for what I want I want the ability to not rely on internet or other devices and that lets me get time and location

I made a lilygo branch and put a rudimentary setup script that builds the GPS example program here (using the command line stuff)
https://github.com/elazarrosenthal/AtcWatchBuilder/blob/lilygo/setuplilygo

Things I like about it over p8
more memory
more devices
gps or sound
sd card
wifi
nice case metal (top back is snap on plastic) - looks like a watch not a pc board strapped to your wrist
normal USB connection for charging and programming no special cables no opening watch (the back snaps off but no special connection needed

things p8 is better on
size smaller lilygo is on the big size
sealed - snap on back on lilygo has holes in it probably would get water damaged if splashed while washing your hands
cost - somewhat cheaper but added
battery life - lilygo is not supposed to last that long from what I have read did not really use to tell for myself








# AtcWatchBuilder

Linux script to build   Aaron Christophel's  ATCWatch 

https://github.com/atc1441/ATCwatch

usage bash setup newdirectory

creates directory newdirectory and downloads needed files there

creates script build in that directory that can be used to compile

I use like

bash setup watchdir > setup.out 2>&1

onece done
cd watchdir and work in there 
the build script set watchdir as its home 
setenv can be used to set HOME and PATH as well


Note:
It would be nice to do somthing similar to this for windows using 
powershell 

powershell has the ablity to do a native equvilant of wget
needed files should be retrivable and placed in the directory 

