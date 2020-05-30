Commands:
=========

X specifies a number  
Arguments between ( ) are optional


Manager+
--------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!add | @user | add user to the waitlist |
|!afklimit | X | sets the maximum afk time |
|!afkremoval | | toggles the afk check |
|!autofav | | make !fav be displayed on a timer |
|!autoplzwoot | | make !plzwoot be displayed on a timer |
|!autoroulette | | make !roulette be displayed on a timer |
|!autoskip | | skips songs automatically when they're done (use when the circles-bug happens) |
|!botname |	(botname) | change the default bot name |
|!bouncer+ | | disable/enable bouncer+ |
|!clearchat | |clears the chat |
|!cycle | | toggle DJ cycle |
|!cycletimer | X | set the maximum DJ cycle time for when cycleguard is enabled |
|!deletechat | @user | delete all the chats by a certain user ***NOT WORKING!*** |
|!language | (language) | specify the language you would like the bot to use |
|!lock | | lock the waitlist |
|!lockdown | | lock down the room: only staff can chat |
|!locktimer | X | set the maximum time the waitlist can be locked if lockguard is enabled |
|!logout | | logs out account bot is hosted on |
|!maxlength | X | specify the maximum length a song can be when timeguard is enabled |
|!move | @user (X) | moves user to position X on the waitlist, default is position 1 |
|!refresh | | refreshes the browser of whoever runs the bot |
|!remove | @user | remove user from the waitlist |
|!roulette | | start a roulette |
|!songstats | | toggle song statistics |
|!unlock | | unlock the waitlist |
|!usercmdcd | X | set the cooldown on commands by grey users |
|!usercommands | | toggle user commands |
|!voteskip | (X) | when no argument is specified, returns the current voteskip limit, when X is specified, voteskip limit is updated to the new specified limit |
|!welcome | | toggle the welcome message on user join |

Bouncer
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!active | (X) | shows how many users chatted in the past X minutes. If no X specified, 60 is set as default |
|!afkreset | @user | resets the afk time of user |
|!afktime | @user | shows how long user has been afk |
|!autodisable | | toggle the autodisable |
|!ban | @user | bans user for 1 day |
|!blacklist / !bl | blacklistname | add the song to the specified blacklist |
|!bleepbloop | (@user) | the trolliest command ever |
|!blinfo | | get information required to blacklist a song |
|!cycleguard | | toggles the cycleguard |
|!dclookup / !dc | (@user) | do dclookup for user |
|!english | @user | ask user to speak english (asked in the language they set plug to) |
|!eta | (@user) | shows when user will reach the booth |
|!filter | | toggles the chat filter |
|!forceskip | | forceskips the current song |
|!jointime | @user | shows how long the user has been in the room |
|!kick | (X) | kicks user for X minutes, default is 0.25 minutes (15 seconds) |
|!kill | | shut down the bot |
|!lockguard | | toggle the lockguard |
|!skip | (reason) | skips, locks and moves the dj back up (the position can be set with !skippos) |
|!motd | (X)/(message) | when no argument is specified, returns the Message of the Day, when X is specified, the MotD is given every X songs, when "message" is given, it sets the MotD to message |
|!mute | @user (X) | mute user, for X minutes if X is specified, otherwise for an undefined period |
|!reload | | reload the bot |
|!restricteta | | toggles the restriction on eta: grey users can use it once an hour |
|!sessionstats | | display stats for the current session |
|!skip | (reason) | skips the dj using smartskip. actions such as locking and moving user depends on various factors (the position the dj is moved to can be set with !skippos) |
|!skippos | X | set the position to which skip and lockskip moves the dj |
|!status | | display the bot's status and some settings |
|!timeguard | | toggle the timeguard |
|!togglebl | | toggle the blacklist |
|!togglemotd | | toggle the motd |
|!togglevoteskip | | toggle the voteskip |
|!unban | @user | unban user |
|!unmute | | unmute user |
|!voteratio | @user | display the vote statistic for a user |
|!whois | @user | returns plug related information about user |

Resident DJ
-----------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!link | | give a link to the current song |



User
----

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!8ball | (message) | ask the bot a question, the bot will return random variations of a yes or no answer |
|!acronym | | 6 random letters will be made, try to make an acronym out of them |
|!autowoot | | links to PlugCubed, the advised script/plugin to use for autowooting |
|!ba | | explains the Brand Ambassador rank |
|!candy | (@user) | give a random candy to a user |
|!commands | | gives a link to the commands |
|!cookie | (@user) | give a cookie to someone |
|!dcinfo | | information about the dc command |
|!dclookup / !dc | | use dclookup on yourself |
|!djcycleinfo | | explains what the djcycle setting does |
|!emoji | | a link to a list with emoji's |
|!eta | | shows how long before you reach the booth |
|!fav | | remind people to favorite the room |
|!fb | | links to the room's Facebook page (not set in settings) |
|!fortune | | get or give a fortune from the bot, the fortune teller |
|!ghostbuster | @user | checks if user is ghosting |
|!gif | (message) | returns a gif (from giphy) related to the tag provided, Returns a random gif if no tags are provided |
|!help | | links to an image to help get people started on plug **NOT AVAILABLE FOR THE MOMENT**|
|!join | | join the roulette if it's up |
|!leave | | leave the roulette if you joined |
|!link | | when the user is the DJ, give a link to the current song |
|!op | | links to the OverPlayed list |
|!ping | | pong! |
|!plzwoot | | reminds people to woot if they're on the dj waitlist |
|!props | (@user) | give "props" to someone for playing a great song |
|!ref | | the "I.T" support command for plug.dj "refresh" |
|!rouletteinfo | | explains the roulette to people who don't know what it is |
|!rules | | links to the rules |
|!shots | (@user) | give someone a shot |
|!staff | | things that are expected from a staff member |
|!theme | | links to the room's theme |
|!website | | links to the room's website (not set in settings) |
|!subinfo | | explain what the plug.dj subscription service means |
|!youtube | | links to the room's youtube page (not set in settings) |


All Sub-Commands
-----------------

|MainCommand | Sub-Command | Description |
|:------:|:---------:|:--------------------------------------:|
|!skip |unavailable | if the song is not available for some, most or all users |
|^ bouncer+| history | if the song is in the "DJ history" |
||nsfw | if the song played contained an NSFW image or sound |
||sound | if the song played had horrible sound quality or no sound |
||theme | if the song doesn't fit the room theme  |

Coming Soon... Hop3fully
-------------------------

|Command | Description | Estimated Time |
|:------:|:---------:|:---------------:|:-----------------------:|
|idk|why not suggest something!||
