# minecraft_item_data
Every single item in minecraft, in json format,, which follows this syntax: `<item name>: give @s <item> 1 <data>`

This is meant for minecraft bedrock (windows 10 edition, play station, xbox, mobile/pocket edition) but it might work on java as well.

The data comes in 5 different formats:
--------------------------------------------------------------------------------------------------------------------------------
default.json: ........................... `<item name seperated by spaces>: give @s <item> 1 <data>`
  
default_with_slash.json: ................ `<item name seperated by spaces>: /give @s <item> 1 <data>`

underscore.json: ........................ `<item name seperated by underscores>: give @s <item> 1 <data>`
  
underscore_with_slash.json: ............. `<item name seperated by underscores>: /give @s <item> 1 <data>`

pretty.json: ............................ `<item name seperated by underscores, the effect names and such have been given some aliases and renamed to fix odd formatting>: give @s <item> 1 <data>`
