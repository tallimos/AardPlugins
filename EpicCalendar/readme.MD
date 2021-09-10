
Tallimos' Epic Calendar v2.21 for Aardwolf MUD
----------------------------------------------
This plugin gives the user an easy way of keeping track of upcoming epic runs as well as some nice few extras. Once installed the user can use the commands below to update the list. Also if a note is posted while the user is online the list will automatically get updated.

Main Commands
-------------
<pre>
<b>ecal update</b>           - checks and see if the latest version of the plugin is installed
<b>ecal reset</b>            - clears the epic run list and adds all upcoming runs
<b>ecal list</b>             - lists all upcoming epic runs
<b>ecal vi</b>               - enables/disables the vi friendly option
<b>ecal tdif</b>             - toggles hour display between mudtime and user's timezone
                        this only affects displays sent to USER ONLY anything sent via channel or note will show mud time as
                        the hour
<b>ecal search (epic)</b>    - searches the epic runs list
<b>ecal nupdate (note #)</b> - used when epic leader posts a subject line to long
<b>ecal checkversion</b>     - checks to see if there is a newer version of the plugin available
<b>ecal changelog</b>        - displays the changelog for the plugin
</pre>

Other Features
--------------
<pre>
<b>ecal help bot</b>  - for more information on a notification and channel command bot
<b>ecal help next</b> - for more information on some useful commands to display the next upcoming epic
<b>ecal help rt</b>   - for more information on some useful commands to display the next upcoming epic
</pre>

<b>PLEASE NOTE</b>: the user can also use epiccalendar instead of ecal

Notification Bot
----------------
The notification bot allows the user to alert themselves of upcoming epic runs. If an epic is going to start within 1 hour or less the system will remind the user about the upcoming epic run.

Also with this system the user can grant whoever they want access to next commands without having to install the plugin themselves. See ecal help next for more information on those commands.

Finally this system will also allow users to post hourly reminders to channels of their choosing of the next up coming epic run.

Main Commands
-------------
<pre>
<b>ecal bot (enable|disable)</b>                           - enables/disables the main bot system
<b>ecal bot (auto|commands) list</b>                       - lists the channels and their settings for the specified system
<b>ecal bot (auto|commands|alert) (enable|disable)</b>     - enables/disables the specified system
<b>ecal bot (auto|commands) (enable|disable) (channel)</b> - enables/disables the channel notification in the specified system
<b>ecal bot (add|remove) room</b>                          - adds/removes the current room to the approved note sending room list
<b>ecal bot list room</b>                                  - displays the list of approved note sending rooms
<b>ecal bot status</b>                                     - displays the status of the notification bot and its features
</pre>

Power User Commands
-------------------
<pre>
<b>ecal bot (add|remove) (player)</b>  - add/removes players to the channel command permission system
<b>ecal bot plist</b>                  - list all players who have access to the channel commands
<b>ecal bot permissions</b>            - toggles channel command access between LIST and ALL. default is set to LIST
</pre>

Blacklist Commands
------------------
<pre>
<b>ecal bot bl (enable|disable)</b>      - enables/disables blacklist for channel command access
<b>ecal bot bl</b>                       - displays who is on the blacklist
<b>ecal bot bl add (player) (reason)</b> - adds a player to the blacklist with the option to add the reason why
<b>ecal bot bl remove (player)</b>       - remove a player from the blacklist

<b>PLEASE NOTE</b>: only ft, gt, clan and tells have been added to the channel command system
</pre>

Next Commands
-------------
The next commands are basically just that, it will show the next epic coming up in various categories.

<pre>
<b>ecal nextepic</b>             - displays to the user which epic run is coming up next
<b>ecal nextepic (epic)</b>      - displays when the next specified epic run is coming up
<b>ecal nextday (day)</b>        - displays the first epic run on a particular day
<b>ecal nextleader (leader)</b>  - displays the next epic run coming up for a particular leader
</pre>

If the user specifies a channel in the above commands then the message will get displayed to that channel. For example 'ecal nextepic inferno ft' will display the next schedule inferno epic run to friend talk. Take Note - to display the next upcoming epic to a channel the user must use ecal nextepic epic <channel>

Channel Command System
----------------------
If the channel command system has been activated the users who have access can using the commands below to see upcoming epic runs

<pre>
<b>!nextepic</b>             - displays the next upcoming epic
<b>!nextepic (epic)</b>      - displays when the next specified epic is scheduled
<b>!nextleader (leader)</b>  - displays the first epic scheduled for that particular leader
<b>!nextday (day)</b>        - displays the first epic of the day on that particular day
<b>!listday</b>              - displays the epic schedule for the current day on one line
<b>!listday (day)</b>        - displays the epic schedule for a particular day on one line
<b>!listepic</b>             - displays the entire epic schedule on one line, sorted by day
<b>!listepic leader</b>      - displays the entire epic schedule on one line, grouped by leader
<b>!listepic epic</b>        - displays the entire epic schedule on one line, sorted by epic name
<b>!listepic (epic name)</b> - displays the full schedule of the epic the user searched for
<b>!listleader (leader)</b>  - displays the full schedule for a particular leader
<b>!listepic note</b>        - will request the bot to send them the schedule via a note
<b>!noteremove (notenum)</b> - will request the bot to remove the schedule note
</pre>
  
User's Guide
------------
https://docs.google.com/document/d/1Ewa9IlA4ZTMRowXQzK1mX-CHGw3Fjys7PhgpWLRRra4/edit?usp=sharing
