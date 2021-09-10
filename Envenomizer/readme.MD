Tallimos' Envenomizer v1.4 for Aardwolf MUD
-------------------------------------------                                
This script will allow any venomist to envenom and return weapons to their owners. You will need a true seeing helm so that if you have true sight casted and it drops then you will still see hidden/invis players. You will need the id number for your true seeing helm as well as the id number for the container it is stored in.

Main Commands
-------------
<pre>
<b>env on (minutes)</b> - turns the envenom system on and broadcasts at regular intervals for the set amount of time
<b>env on</b>           - turns the envenom system on without an automatic broadcast
<b>env off</b>          - turns the envenom system off
<b>env ons</b>          - turns the envenom system on in silent mode
<b>env all</b>          - envenom all weapons given to user
<b>checkweapons</b>     - used at the end to returned any owned weapons to their owners that got missed
<b>env weapons</b>      - envenoms all weapons in owner's inventory
</pre>

Broadcast Commands
------------------
<pre>
<b>env bc (channel)</b> - sets the broadcast channel
<b>env bc</b>           - shows what channel the user has set for broadcasting, default is gt
<b>env nc</b>           - repeats report channel messages for new comers can also use env new and env newcomers
<b>env lc</b>           - sends a last call for envenoms message to report channel can also use env lastcall
</pre>

Other Commands
--------------
<pre>
<b>env settimer (minutes)</b> - sets the interval for each automatic broadcast
<b>env helm (idnum)</b>       - used to set the id number of your true seeing helm command can be shorten to env h
<b>env bag (idnum)</b>        - used to set the id number of the container which holds your true seeing helm command can be shorten to env b
</pre>

Please Note: I do not mind answering questions about this script but I will not be providing support for it. However, if you do have an idea for the script and I think it is great and I can code it I will add it if/when I have time.

Thank you.

  
