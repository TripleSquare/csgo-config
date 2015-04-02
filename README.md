# Counter Strike: Global Offensive
###config used by TripleSquare


My config for cs:go contains alot of files, i hope it is easier to understand this way.

_on a later point of time i may or may not create a clear list of all my keybinds_



##First Steps:


###1. Set launch options for cs:go.

To do this: 

start steam -> switch to Libary -> search Counter Strike: Global Offensive -> right click -> Properties -> (General Tab) Set launch options

launch options i use (optimized for my rig + Monitor)

´´´
-novid -freq 120 -language english -high -threads 8 +exec autoexec.cfg
´´´
*unless you don't have a Monitor capable of 120Hz (-freq 120) and a CPU with atleast 8 cores (-threads 8) those values are useless for you.*

If you have a PC with a Quadcore CPU ( Desktop Intel i5 & i7, Mobile i7 or Desktop AMD Phenom X4 & FX-4xxx ) use the launch options below
worth mentioning is that i've removed the "-freq 120" because most Monitors aren't able to handle those 120Hz refresh rates. 

´´´
-novid -language english -high -threads 4 +exec autoexec.cfg
´´´


###2. config files

To install those you'll have to download the files you're interested in form the /cfg folder.

File and what it does: 



autoexec.cfg 

´loading all the other *.cfg's, basic viewmodel settings and some other handy stuff´



_viewmodel.cfg

´csgo viewmodel, the way you hold your gun´

Usefull Steam Workshop Map to test around: [crashz' Viewmodel Generator](https://steamcommunity.com/sharedfiles/filedetails/?id=365126929)



_crosshair.cfg

´my crosshair settings i use´

again a usefull Steam Workshop Map to create your own: [crashz' Crosshair Generator v2](https://steamcommunity.com/sharedfiles/filedetails/?id=308490450)



_buyscript.cfg

´numpad keybinds for buying weapons´

Usefull website to generate your own keybinds (not only for the numpad) [csgobindsgenerator.com](http://csgobindsgenerator.com/)



_keybinds.cfg

´most of the keybinds my config includes´



_addons.cfg

´Netgraph when pressing Tab, smaller map when pressing use key, jump'n'throw for grenades, Helplines for Smokes and Damage Display on Top Left corner´

Thanks to [bananagaming](https://www.youtube.com/user/OfficialBananaGamers) for those addons



_config.cfg

´the rest of my client settings´



video.txt

´video settings i use´



###3. after copying those files

make those read only! 