---
layout: default
title: "Get Started"
permalink: /getstarted/
---

# Install GD and Geode
First thing you want to do is buy and download GD on steam, this guide will not account for pirated versions of the game

Next launch and then quit the game and head to [geode-sdk.org](https://geode-sdk.org) and download Geode  
Make sure you run `usermod -aG input $USER` with sudo after downloading geode and **RESTART YOUR PC** otherwise the changes won't apply

Next head into steam, right click on geometry dash, select properties and in launch options add these launch options:
`WINEDLLOVERRIDES="xinput1_4=n,b" vblank_mode=0 %command%`

The first option WINEDLLOVERRIDES tells the game to load the Geode mod manager **MANDATORY**  
The next option vblank_mode=0 disables vsync allowing for lower input latency and is completely optiopnal

You will also want to go into the compatibility tab and select a custom version of proton.  
I recommend using the cachyos proton or the GE proton versions as they offer better optimization.  
To learn more about proton versions and how to get them go to the [Proton page](proton)

Now you should have GD with Geode installed, this is probably enough for most players, you can now install all the mods you want.  
However if you want to use CBF with the wine workaround proceed onto the [next step.](cbf)
