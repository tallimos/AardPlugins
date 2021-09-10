Tallimos' Epic Broadcaster v1.81 for Aardwolf MUD
-------------------------------------------------
This plugin gives the user an easy to use broadcaster for announcing epic run groupings.

Main Commands
-------------
teb update                     - checks for the latest version of plugin and installs it<br />
teb checkversion               - checks to see if there is a newer version of the plugin available<br />
teb changelog                  - displays the changelog for the plugin<br />
teb <enable|disable> <channel> - enables/disables broadcasting for that particular channel<br />
teb list                       - lists the channels and their broadcasting status<br />
teb cancel                     - cancels the automatic broadcasting<br />
teb settimer <minutes>         - sets the time for each automatic broacast<br />
teb namedisplay                       - toggles between Full and Short for epic name<br />
teb vi                                - enables/disables the vi friendly option<br />
teb setdisplay <num>                  - sets the display type.<br />
  
Displays 1-20 are the normal displays, Displays 21-40 are similar but displays epic with (Mentor) flag<br />
teb sample (display number|epic name) - displays an example of the broadcast message using current settings.<br />
if optional display number is inputted the sample message will be of that display type.<br />
if optional epic name is inputted it will show what the epic display name will appear as<br />
teb setcolour <epic name> <colourcode> - sets colour code for that particular epic<br />
teb broadcast <epic name> (minutes til epic) (optional message) - starts the broadcasting system.<br />
If the user does not input the number of minutes until the epic starts, then the grouping announcement will only broadcast once.<br />
If included the system will figure out the number of broadcasts and will start and finish broadcasting automatically including a last call.<br />
Any optional message will get added to the end of the broadcast message<br />
<br />
Valid epic names are: genie, if1, if2, inferno, oc, winds, titan, terra, oldvanir, testmaze10 and trans
