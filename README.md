# 3ds_cci_info
#### USA_all/
Ctrtool info output for complete cci (.3ds) sets.
#### USA_special_lists/ 
These are special lists of 3ds cart titles that contain certain traits that could be useful to vuln research/dev.
* extdata.txt - has sd extdata. with seedminer, it is possible to modify these saves from PC for hax. Ex.  
https://github.com/zoogie/Kartminer7
* sdmc.txt - read/write data to sd card. makes it easier to fit a nice secondary payload. not usually necessary but nice to have. (note that the "Etrian" game series is write-only for some reason)
* extdata_and_sdmc.txt - has the above two at once. super nice!
* powersaves.txt - early cart saves have lousy crypto and can be edited by the powersaves savegame dongle and DS phat/lite. Ex.
	https://github.com/yellows8/oot3dhax
* dlp.txt - has download play lan for local multiplayer. 3DSdlp has proven to be exploitable if you have a 2nd haxed 3ds. Ex.
	https://github.com/PabloMK7/kartdlphax
	https://github.com/Wack0/pialeasenerf-PoC
##### Notes:
* All of the above applies to the cart's eShop version as well, except for the powersaves weak crypto vuln
* EUR_all and JPN_all lists aren't provided, but PRs are welcome. the usa list should be fine for general research since most have corresponding versions in other regions.
* How did you generate the special lists? Just simple filter scripts, not worth posting here. if someone provides "EUR_all" or "JPN_all", I can do the rest. it's a big job to download all of that though!