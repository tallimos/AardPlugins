 Tallimos' AutoInviter v1.62 for Aardwolf MUD
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
This plugin gives the user an easy to use auto inviter with blacklist and power user options.
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

Main Commands
-------------
tai update                   - checks for the latest version of plugin and installs it
tai checkversion             - checks to see if there is a newer version of the plugin available
tai changelog                - displays the changelog for the plugin
tai enable                   - enables the autoinviter system
tai disable                  - disables the autoinviter system
tai vi                       - enables/disables the vi friendly option
tai bonk                     - enables/disables the bonk sent when someone is already in a
                               group
tai check <player>           - checks to see if player is in group or not (i.e. Talia check)
tai pending                  - shows the pending invites
tai lock                     - locks the group and turns off the autoinvite without disabling
                               system
tai unlock                   - unlocks the group and turns back on the autoinvite
tai autounlock <num>         - autolocks the group after group count reachs a certain point

Keyword Commands
----------------
tai keywords                 - lists your autoinvite keywords
tai keyword add <keyword>    - adds keyword to the keyword list. can be made up of multiple
                               words
tai keyword remove <keyword> - remove keyword from the keyword list

Blacklist Commands
------------------
tai bl enable                - enables the blacklist
tai bl disable               - disables the blacklist
tai bl                       - displays who is on the blacklist
tai bl add <player> <reason> - adds a player to the blacklist with the option to list the
                               reason why
tai bl remove <player>       - remove a player from the blacklist

Power User Commands
-------------------
tai pusers                   - lists your approved power users
tai puser enable             - enables the power user commands
tai puser disable            - disables the power user commands
tai puser add <player>       - adds player to power users list
tai puser remove <player>    - remove player from power users list

PLEASE NOTE: For a list of power user commands, type .help on grouptell while the Power User
system is ENABLED.
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
