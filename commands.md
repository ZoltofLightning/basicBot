Commands:
=========

X specifies a number  
Arguments between ( ) are optional

Host
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!logout | | logout the bot. |


CoHost
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!bouncer+ | | disable bouncer+ |
|!botname | (botname) | change the bot name |
|!kill | | shut down the bot |
|!language | (language) | specify the language you would like the bot to use |
|!lockskippos | X | set the position to which lockskip moves the dj |
|!refresh | | refreshes the browser of the bot. |
|!reload | | reload the bot |


Manager
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!afklimit | X | sets the maximum afk time |
|!afkremoval | | toggles the afk check |
|!autodisable | | toggle the autodisable |
|!autoskip | | skips songs automatically when they're done (use when the circles-bug happens) |
|!blacklist / !bl | blacklistname | add the song to the specified blacklist |
|!clearchat | |clears the chat |
|!cmddel | |toggles commands being deleted. |
|!cycle | | toggle DJ cycle |
|!cycletimer | X | set the maximum DJ cycle time for when cycleguard is enabled |
|!filter | | toggles the chat filter |
|!lock | | lock the waitlist |
|!lockdown | | lock down the room: only staff can chat |
|!locktimer | X | set the maximum time the waitlist can be locked if lockguard is enabled |
|!lockskip | (reason) | skip the song and move the dj back up (the position can be set with !lockskippos) |
|!maxlength | X | specify the maximum length a song can be when timeguard is enabled |
|!motd | (X)/(message) | when no argument is specified, returns the Message of the Day, when X is specified, the MotD is given every X songs, when "message" is given, it sets the MotD to message |
|!move | @user (X) | moves user to position X on the waitlist, default is position 1 |
|!roulette | | start a roulette |
|!songstats | | toggle song statistics |
|!swap |(user 1) (user 2)| swap a user with another user in the waitlist |
|!togglebl | | toggle the blacklist |
|!togglemotd | | toggle the motd |
|!togglevoteskip | | toggle the voteskip |
|!unban | @user | unban user |
|!usercmdcd | X | set the cooldown on commands by grey users |
|!usercommands | | toggle user commands |
|!voteskip | (X) | when no argument is specified, returns the current voteskip limit, when X is specified, voteskip limit is updated to the new specified limit. |
|!welcome | | toggle the welcome message on user join |

Bouncer
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!active | (X) | shows how many users chatted in the past X minutes. If no X specified, 60 is set as default |
|!add | @user | add user to the waitlist |
|!afktime | @user | shows how long user has been afk |
|!afkreset | @user | resets the afk time of user |
|!ban | @user | bans user for 1 day |
|!blinfo | | get information required to blacklist a song |
|!cycleguard | | toggles the cycleguard |
|!dclookup / !dc | (@user) | do dclookup for user |
|!english | @user | ask user to speak english (asked in the language they set plug to) |
|!eta | (@user) | shows when user will reach the booth |
|!ghostbuster | @user | checks if user is ghosting |
|!historyskip | @user | Sets the bot to skip recently played songs |
|!jointime | @user | shows how long the user has been in the room |
|!kick | (X) | kicks user for X minutes, default is 0.25 minutes (15 seconds) |
|!lockguard | | toggle the lockguard |
|!mute | @user (X) | mute user, for X minutes if X is specified, otherwise for an undefined period |
|!remove | @user | remove user from the waitlist |
|!restricteta | | toggles the restriction on eta: grey users can use it once an hour |
|!sessionstats | | display stats for the current session |
|!skip | | skip the current song |
|!status | | display the bot's status and some settings |
|!timeguard | | toggle the timeguard |
|!unlock | | unlock the waitlist |
|!unmute | | unmute user |
|!voteratio | @user | display the vote statistic for a user |
|!whois | @user | returns plug related information about user |

Resident DJ
-----------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!8ball / !ask | (message) | ask the bot a question, the bot will return random variations of a yes or no answer. |
|!cookie | (@user) | give a cookie to user |
|!dclookup / !dc | | use dclookup on yourself |
|!emoji | | a link to a list with emoji's |
|!eta | | shows how long before you reach the booth |
|!gif | (message) | returns gif (from giphy) related to the tag provided. Returns a random gif if no tags are provided. |
|!join | | join the roulette if it's up |
|!leave | | leave the roulette if you joined |
|!link | | give a link to the current song

User
----

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!autowoot | | links to PlugCubed, the advised script/plugin to use for autowooting |
|!ba | | explains the Brand Ambassador rank |
|!commands | | gives a link to the commands |
|!fb | | links to the room's Facebook page (if set in the settings) |
|!help | | links to an image to help get people started on plug |
|!op | | links to the OverPlayed list (if set in the settings) |
|!ping | | pong! |
|!rules | | links to the rules (if set in the settings) |
|!theme | | links to the room's theme (if set in the settings) |
|!website | | links to the room's website (if set in the settings) |
|!youtube | | links to the room's youtube page (if set in the settings) |
