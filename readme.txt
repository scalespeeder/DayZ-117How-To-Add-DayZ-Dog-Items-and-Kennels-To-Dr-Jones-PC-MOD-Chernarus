DayZ 1.17 Chernarus DayZ Dog Kennels At Trader & New "Pet Supplies" Category For Use With Dr Jones Trader

THESE ARE THE TEXT SNIPPETS FOR THOSE THAT WOULD LIKE TO MODIFY THEIR OWN TRADER CONFIG FILES,
PROBABLY BEACUSE YOU HAVE OTHER MODDED ITEMS ALREADY INCLUDED, OR DAYZ HAS MOVED BEYOND 1.7.

(HOWEVER, IF YOU ARE RUNNING A VANILLA 1.17 DR JONES TRADER MOD, SIMPLY UPLOAD THE TraderConfig.txt & TraderObjects.txt
FILES TO YOUR TRADER CONFIG / PROFILES FOLDER ON YOUR SERVER.)

MANY THANKS TO DR JONES!

YOU MUST HAVE DR JONES TRADER AND DAYZ DOG MODS INSTALLED AND WORKING FOR THESE EDITS TO WORK!

PLEASE NOTE THAT NOT ALL SURVIVORS CAN "CALL" A DOG FROM A KENNEL. IF STILL SO AFTER A RESTART THAT SURVIVOR WILL
PROBABLY ONLY BE ABLE TO "CALL" A DOG ON THEIR NEXT LIFE.

ADD THIS TO THE SECOND HALF OF TRADEROBJECTS.TXT, BELOW // Green Mountain:

<Object> dog_shed_small_static
<ObjectPosition> 3696.31005859375, 401.9519958496094, 5970.58984375
<ObjectOrientation> -23.88699722290039, 0, 0

AND BELOW // Kumyrna:

<Object> dog_shed_small_static
<ObjectPosition> 8351.169921875, 291.9559631347656, 5978.7099609375
<ObjectOrientation> -82.53368377685547, 0, 0

save (and upload if necessary) to trader config folder on your server (inside the server profile / config / settings folder)

ADD THESE TO TraderConfig.txt BELOW THE LAST ENTRY IN <Category> Hardware Supplies:

<Category> Pet Supplies
		dog_shed_small_kit,		*,		20,		-1
		dog_shed_wooden_kit		*,		50,		-1
		dog_shed_big_kit,		*,		100,	-1
		dog_bowl,				*,		10,		-1
		dog_bone_toy,			*,		10,		-1
		
save (and upload if necessary) to trader config folder on your server (inside the server profile / config / settings folder)