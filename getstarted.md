---
layout: default
title: "Get Started"
permalink: /getstarted/
---
[go back](../)

# Install GD and Geode
First thing you want to do is buy and download GD on steam, this guide will not account for pirated versions of the game

Next launch and then quit the game and head to [geode-sdk.org](https://geode-sdk.org) and download Geode  
If you want CBF make sure you run `usermod -aG input $USER` with sudo after downloading geode and **RESTART YOUR PC** otherwise the changes won't apply

Next head into steam, right click on geometry dash, select properties and in launch options add these launch options:
`WINEDLLOVERRIDES="xinput1_4=n,b" %command%`

The option WINEDLLOVERRIDES tells the game to load the Geode mod loader and is **MANDATORY**  

You will also want to go into the compatibility tab and select a custom version of proton.  
I recommend using the cachyos proton or the GE proton versions as they offer better optimization.  
To learn more about proton versions and how to get them go to the [Proton page](../proton)

Now you should have GD with Geode installed, this is probably enough for most players, you can now install all the mods you want.  
However if you want to use CBF with the wine workaround proceed onto the [next step.](../cbf)
