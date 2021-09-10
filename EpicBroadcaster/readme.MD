Tallimos' Epic Broadcaster v1.81 for Aardwolf MUD
-------------------------------------------------
This plugin gives the user an easy to use broadcaster for announcing epic run groupings.

Main Commands
-------------
<b>teb update</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- checks for the latest version of plugin and installs it<br />
<b>teb checkversion</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- checks to see if there is a newer version of the plugin available<br />
<b>teb changelog</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- displays the changelog for the plugin<br />
<b>teb <enable|disable> <channel></b> - enables/disables broadcasting for that particular channel<br />
<b>teb list</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- lists the channels and their broadcasting status<br />
<b>teb cancel</b>                     - cancels the automatic broadcasting<br />
<b>teb settimer <minutes></b>         - sets the time for each automatic broacast<br />
<b>teb namedisplay</b>                       - toggles between Full and Short for epic name<br />
<b>teb vi</b>                                - enables/disables the vi friendly option<br />
<b>teb setdisplay <num></b>                  - sets the display type.<br />
  
Displays 1-20 are the normal displays, Displays 21-40 are similar but displays epic with (Mentor) flag<br />

<b>teb sample (display number|epic name)</b> - displays an example of the broadcast message using current settings.<br />
if optional display number is inputted the sample message will be of that display type.<br />
if optional epic name is inputted it will show what the epic display name will appear as<br />

<b>teb setcolour <epic name> <colourcode></b> - sets colour code for that particular epic<br />

<b>teb broadcast <epic name> (minutes til epic) (optional message)</b> - starts the broadcasting system.<br />
If the user does not input the number of minutes until the epic starts, then the grouping announcement will only broadcast once.<br />
If included the system will figure out the number of broadcasts and will start and finish broadcasting automatically including a last call.<br /><br />
<i>Any optional message will get added to the end of the broadcast message</i><br />
<br />
Valid epic names are: genie, if1, if2, inferno, oc, winds, titan, terra, oldvanir, testmaze10 and trans
