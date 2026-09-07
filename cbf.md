---
layout: default
title: "CBF Setup"
permalink: /cbf/
---

# To get CBF working properly requires a couple more steps
First download Click Between Frames within Geode, make sure wine workaround option is selected and quit the game.  
If you use any version of proton before 11.0 that is enough and CBF will now work  
If you use proton versions 11.0 and later then some additional steps are needed

## Proton 11.0+
If you are running latest proton you need the `LD_PRELOAD="/usr/lib/libevdev.so.2" WINEDLLOVERRIDES="xinput1_4=n,b" %command` launch options in steam  
CBF has a problem preloading the library needed for it to work  
Also note if it takes over 5 seconds to load a level, CBF might fail to work

## General CBF info
Make sure Wine workaround is on **EXCEPT** if you are on Wayland in that case it shouldn't matter if using the `PROTON_ENABLE_WAYLAND=1 WINEDLLOVERRIDES="xinput1_4=n,b" %command` launch options  
If your clicks are registering twice or not at all, either restart the game or you missed a step
