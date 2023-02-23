# RDR1-Undead-Weapons-Online
-2/23/2023 added ps3 mem pointer to block wep deletes. ER bypass is still required to make this work properly, however without er bypass a few of the weapons will work as is.

This is the source code to get undead weapons online in freeroam as well as mp gamemodes other than undead overrun. 


This should work on any rdr version (so long as undead dlc is installed or using undead nightmare base game)

You get blunderbuss, torch, holy water, zombie bait, zombie boom bait, & zombie spit online.
- You must ER Bypass at mainmenu to use all weapons.
- Without er bypassing at mainmenu only a few undead weps will work.
- In order to use zombie boom bait or zombie spit, you must use demonic rev weapon spawner to force those weapons in your hand or use the example function in example.c
- In example.c you will see a force weapon in hand function, and you will also see the pointer that allows blunderbuss, torch, and er without having to ER bypass.
- That pointer only works with the above mentioned game version. Feel free to find that same pointer on diff game versions/platforms.
- This script should work fine on a retail console via iso modding (xbox 360) so long as you remove the memory pointer in the script. 

- Video on how to ER Bypass works pretty much the same on xbox 360 and ps3: https://www.youtube.com/watch?v=JeBuLUAxGUE
- At mainmenu where it says press start, just unplug your ethernet cable and press start at the same time, replug ethernet cable back in, wait 10-15 seconds and sign back into xbl/psn then go online and if you spawn with the explosive rifle (er) then you did it correctly.

Created by Sockstress (Райан) & CabooseSayzWTF

Help from ImFoxxyyy & Cain532 for native documentation
