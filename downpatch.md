---
layout: default
title: "Downpatch Guide"
permalink: /downpatch/
---
[go back](../)

# Open Steam console
Make sure you close steam completely, then go to the terminal and launch steam with `steam -console`  
On windows simply open [this](steam://open/console) link  

# Download the 2.208 patch
Next enter this command in the console `download_depot 322170 322171 3816559102876907245`  
Now make sure to update the ACF file for geometry dash so the game does not auto update  
Head to `~/.local/share/Steam/steamapps` and edit the 322170.acf to say **"StateFlags"		"4"**  
On windows the path will be `(install_location)/Steam/steamapps `

# Replace the files
Right click GD in steam and browse local files, and replace the game files with the ones downloaded in the console  
The console outputs the path of the downloaded patch
