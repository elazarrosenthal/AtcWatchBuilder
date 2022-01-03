# AtcWatchBuilder
Script to build AtcWatch https://github.com/atc1441/ATCwatch
under linux 

usage bash setup newdirectory

creates directory newdirectory and downloads needed files there

creates script build in that directory that can be used to compile

I use like

bash setup watchdir > setup.out 2>&1

onece done
cd watchdir and work in there 
the build script set watchdir as its home 
setenv can be used to set HOME and PATH as well

