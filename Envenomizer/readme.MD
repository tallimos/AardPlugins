Tallimos' Envenomizer v1.4 for Aardwolf MUD
-------------------------------------------                                


This script will allow any venomist to envenom and return weapons to their owners. You will need a true seeing helm so that if you have true sight casted and it drops then you will still see hidden/invis players. You will need the id number for your true seeing helm as well as the id number for the container it is stored in.

Main Commands
-------------

env on <minutes> - turns the envenom system on and broadcasts at regular intervals for the set amount of time
  
env on  - turns the envenom system on without an automatic broadcast
  
env off - turns the envenom system off
  
env ons - turns the envenom system on in silent mode
  
env all - envenom all weapons given to user
  
checkweapons - used at the end to returned any owned weapons to their owners that got missed
  
env weapons - envenoms all weapons in owner's inventory

Broadcast Commands
------------------
env bc <channel> - sets the broadcast channel
  
env bc  - shows what channel the user has set for broadcasting, default is gt
  
env nc  - repeats report channel messages for new comers can also use env new and env newcomers
  
env lc  - sends a last call for envenoms message to report channel can also use env lastcall

Other Commands
--------------
env settimer <minutes> - sets the interval for each automatic broacast
  
env helm <idnum> - used to set the id number of your true seeing helm command can be shorten to env h
  
env bag <idnum>  - used to set the id number of the container which holds your true seeing helm command can be shorten to env b

Please Note: I do not mind answering questions about this script but I will not be providing support for it. However, if you do have an idea for the script and I think it is great and I can code it I will add it if/when I have time.

Thank you.

  
