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

