---
layout: default
title: "Tweaks"
permalink: /tweaks/
---
[go back](../)

This last section will cover will cover why any other tweaks are just pointless except maybe gamemode  

The launch option `gamemoderun` requires the gamemode package, simply install it with your package manager  
It offers basic game optimizations and is recommended for most games

Most of the stuff that can be optimized already has been by custom proton versions and kernels  
If you use the cachyos kernel and proton you have done as much as can be done for your input latency and performance  

# Fake Tweaks
Be aware many people will put random stuff in their launch options and tell you it has an effect  
For example setting environment variables like DXVK_FRAME_RATE=0 or DXVK_LOW_LATENCY=1  
Geometry Dash uses OpenGL and not DirectX so these commands will do nothing  
