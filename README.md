
# HCDeaths

This addon displays and logs hardcore deaths for Turtle like wow server.
You can move the toast or log by holding ctrl and shift and dragging.
You can reset the toast or log position by holding ctrl and shift and right clicking.

## Commands:
- /hcd message - toggle system death messages
- /hcd window num - hook death messages to a specific chat window
- /hcd move - toggles the toast so you can move it
- /hcd log - toggle death log
- /hcd log scale num - sets the death log scale to num
- /hcd toast - toggle toast popups
- /hcd toast scale num - sets the toast popup scale to num
- /hcd toast time num - sets the number of seconds the toast will display to num
- /hcd progress - toggle level progress toasts
- /hcd color - toggle toast ring colors
- /hcd deathsound - toggle toast deathsounds
- /hcd levelsound - toggle toast levelsounds
- /hcd reset - reset settings

## Death Logs:

Hardcore deaths will be saved to *"\WTF\Account\ACCOUNTNAME\SavedVariables\HCDeaths.lua"*.

Example of an entry in SavedVariables\HCDeaths.lua:

```
	[1] = {
		["zone"] = "Elwynn Forest",
		["stime"] = "01:41:46",
		["killerName"] = "Natural Causes",
		["killerClass"] = "ENV",
		["killerLevel"] = "nil",
		["lastWords"] = "nil",
		["playerClass"] = "Rogue",
		["playerLevel"] = 10,
		["sdate"] = "2023/11/06",
		["hcType"] = "HC",
		["playerName"] = "Tents",
		["deathType"] = "PVE",
	},
```
