Tallimos' Epic Broadcaster v1.81 for Aardwolf MUD
-------------------------------------------------
This plugin gives the user an easy to use broadcaster for announcing epic run groupings.

Main Commands
-------------
teb update                     - checks for the latest version of plugin and installs it

teb checkversion               - checks to see if there is a newer version of the plugin available

teb changelog                  - displays the changelog for the plugin

teb <enable|disable> <channel> - enables/disables broadcasting for that particular channel
  
teb list                       - lists the channels and their broadcasting status
  
teb cancel                     - cancels the automatic broadcasting
  
teb settimer <minutes>         - sets the time for each automatic broacast
  
teb namedisplay                       - toggles between Full and Short for epic name
  
teb vi                                - enables/disables the vi friendly option
  
teb setdisplay <num>                  - sets the display type
  
                                      - Displays 1-20 are the normal displays, Displays 21-40 are similar but displays epic with (Mentor) flag

teb sample (display number|epic name) - displays an example of the broadcast message using current settings
  
                                      - if optional display number is inputted the sample message will be of that display type
  
                                      - if optional epic name is inputted it will show what the epic display name will appear as

teb setcolour <epic name> <colourcode> - sets colour code for that particular epic

teb broadcast <epic name> (minutes til epic) (optional message) - starts the broadcasting system. If the user does not input
                                 the number of minutes until the epic starts, then the grouping
                                 announcement will only broadcast once. If included the system
                                 will figure out the number of broadcasts and will start and
                                 finish broadcasting automatically including a last call.

                                 - Any optional message will get added to the end of the broadcast message

Valid epic names are: genie, if1, if2, inferno, oc, winds, titan, terra, oldvanir, testmaze10 and trans
