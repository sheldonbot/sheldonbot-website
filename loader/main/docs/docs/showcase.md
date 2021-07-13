[Aops](#aops), [Ascii](#ascii), [Book](#book), [Chemistry](#chemistry), [DisableCommand](#disablecommand), [Help](#help), [Invite](#invite), [Math](#math), [Morse](#morse), [OfflineUser](#offlineuser), [Poly](#poly), [Prime](#prime), [Server](#server), [ServerStats](#serverstats), [Sheldon](#sheldon), [Time](#time), [Tools](#tools), [Uptime](#uptime), [UrbanDict](#urbandict), [VoteKick](#votekick), [WatchURL](#watchurl), [Welcome](#welcome), [Wiki](#wiki)

## Aops
####	Aops Cog (1 command) - Aops.py Extension:
	  sc.aops [args...]
	     └─ Gives random math questions

## Ascii
####	Ascii Cog (1 command) - Ascii.py Extension:
	  sc.ascii [text]
	     └─ Beautify some text (font list at http://artii.herokuapp.com/fonts_list).

## Book
####	Book Cog (1 command) - Book.py Extension:
	  sc.book [args...]
	     └─ Returns details about books.

## Chemistry
####	Chemistry Cog (9 commands) - Chemistry.py Extension:
	  sc.balance [args...]
	     └─ Enter the equation in the form A<space>+<space>B<space>=><space>C<space>+<spa...
	  sc.borbital <n>
	     └─ Returns the energy of nth orbital in Bohr's isoelectronic species
	  sc.combustion <com>
	     └─ Returns the combustion reaction for a hydrocarbon
	  sc.compound <n>
	     └─ Returns the details of the compound(Please enter the formula only)
	  sc.element [args...]
	     └─ Returns all details of the element(Please enter the symbol only).
	  sc.em [args...]
	     └─ Gives the properties of electromagnetic wave
	  sc.gal-cell <el1> <el2>
	     └─ Returns properties of a galvanic cell
	  sc.mole <compound> <qty> <number>
	     └─ <compound> <grams/moles/molecules> <number> returns the properties
	  sc.pubchem [args...]
	     └─ Retrieves compound information from PubChem Servers

## DisableCommand
####	DisableCommand Cog (9 commands) - DisableCommand.py Extension:
	  sc.adminallow [yes_no]
	     └─ Sets whether admins can access disabled commands (admin-only).
	  sc.badminallow [yes_no]
	     └─ Sets whether bot-admins can access disabled commands (admin-only).
	  sc.disable [command_or_cog_name]
	     └─ Disables the passed command or all commands in the passed cog (admin-only).  ...
	  sc.disableall 
	     └─ Disables all enabled commands outside this module (admin-only).
	  sc.disabledreact [yes_no]
	     └─ Sets whether the bot reacts to disabled commands when attempted (admin-only).
	  sc.enable [command_or_cog_name]
	     └─ Enables the passed command or all commands in the passed cog (admin-only).  C...
	  sc.enableall 
	     └─ Enables all disabled commands (admin-only).
	  sc.isdisabled [command_or_cog_name]
	     └─ Outputs whether the passed command - or all commands in a passed cog are disa...
	  sc.listdisabled 
	     └─ Lists all disabled commands (admin-only).

## Help
####	Help Cog (3 commands) - Help.py Extension:
	  sc.dumphelp [tab_indent_count]
	     └─ Dumps a timestamped, formatted list of commands and descriptions into the sam...
	  sc.dumpmarkdown 
	     └─ Dumps a timestamped, markdown-formatted list of commands and descriptions int...
	  sc.help [command]
	     └─ Lists the bot's commands and cogs.

## Invite
####	Invite Cog (1 command) - Invite.py Extension:
	  sc.invite [invite_url]
	     └─ Outputs a url you can use to invite me to your server.

## Math
####	Math Cog (3 commands) - Math.py Extension:
	  sc.base <number> <base1> <base2>
	     └─ <number> <original base> <new base> returns the number in the new base
	  sc.factorial <n>
	     └─ Returns factorial of the number passed
	  sc.math [args...]
	     └─ For simple math

## Morse
####	Morse Cog (2 commands) - Morse.py Extension:
	  sc.morse [content]
	     └─ Converts ascii to morse code.  Accepts a-z and 0-9.  Each letter is comprised...
	  sc.morsetable [num_per_row]
	     └─ Prints out the morse code lookup table.

## OfflineUser
####	OfflineUser Cog (1 command) - OfflineUser.py Extension:
	  sc.remindoffline [yes_no]
	     └─ Sets whether to inform users that pinged members are offline or not.

## Poly
####	Poly Cog (2 commands) - Poly.py Extension:
	  sc.factor [args...]
	     └─ Factors the equation. (if it is factorable!!!)
	  sc.findroot [args...]
	     └─ Returns the roots of the equation in x

## Prime
####	Prime Cog (5 commands) - Prime.py Extension:
	  sc.ispr <n>
	     └─ Checks whether the number given is prime.
	  sc.listpr <n> <k>
	     └─ Lists all the prime numbers from the frist number to the second number.
	  sc.nextpr <n>
	     └─ Gives the next nearest prime number.
	  sc.npr <n>
	     └─ Gives the nth prime number.
	  sc.prevpr <n>
	     └─ Gives the previous nearest prime number.

## Server
####	Server Cog (4 commands) - Server.py Extension:
	  sc.getprefix 
	     └─ Output's the server's prefix - custom or otherwise.
	  sc.info 
	     └─ Displays the server info if any.
	  sc.setinfo [word]
	     └─ Sets the server info (bot-admin only).
	  sc.setprefix [prefix]
	     └─ Sets the bot's prefix (bot-admin only).

## ServerStats
####	ServerStats Cog (10 commands) - ServerStats.py Extension:
	  sc.allmessages 
	     └─ Lists the number of messages I've seen on all severs so far. (only applies af...
	  sc.firstjoins 
	     └─ Lists the first users to join.
	  sc.joinedatpos <position>
	     └─ Lists the user that joined at the passed position.
	  sc.joinpos [member]
	     └─ Tells when a user joined compared to other users.
	  sc.listbots <guild_name>
	     └─ Lists up to the first 20 bots of the current or passed server.
	  sc.messages 
	     └─ Lists the number of messages I've seen on this sever so far. (only applies af...
	  sc.recentjoins 
	     └─ Lists the most recent users to join.
	  sc.serverinfo [guild_name]
	     └─ Lists some info about the current or passed server.
	  sc.sharedservers [member]
	     └─ Lists how many servers you share with the bot.
	  sc.users 
	     └─ Lists the total number of users on all servers I'm connected to.

## Sheldon
####	Sheldon Cog (1 command) - Sheldon.py Extension:
	  sc.sheldon 
	     └─ Who... who are you?

## Time
####	Time Cog (6 commands) - Time.py Extension:
	  sc.listtz [tz_search]
	     └─ List all the supported TimeZones in PM.
	  sc.offset [member]
	     └─ See a member's UTC offset.
	  sc.setoffset [offset]
	     └─ Set your UTC offset.
	  sc.settz [tz]
	     └─ Sets your TimeZone - Overrides your UTC offset - and accounts for DST.
	  sc.time [offset]
	     └─ Get UTC time +- an offset.
	  sc.tz [member]
	     └─ See a member's TimeZone.

## Tools
####	Tools Cog (5 commands) - Tools.py Extension:
	  sc.bot_info 
	     └─ Returns bot_info.
	  sc.dmhelp 
	     └─ Gives dm help.
	  sc.echo <message>
	     └─ Echose your message
	  sc.ping 
	     └─ Returns bot latency.
	  sc.suggest [args...]
	     └─ You can now send suggestions directly to the creators

## Uptime
####	Uptime Cog (1 command) - Uptime.py Extension:
	  sc.uptime 
	     └─ Lists the bot's uptime.

## UrbanDict
####	UrbanDict Cog (2 commands) - UrbanDict.py Extension:
	  sc.define [word]
	     └─ Gives the definition of the word passed.
	  sc.randefine 
	     └─ Gives a random word and its definition.

## VoteKick
####	VoteKick Cog (13 commands) - VoteKick.py Extension:
	  sc.setvkchannel [channel]
	     └─ Sets which channel then mention posts to when enough votes against a user are...
	  sc.setvkmention [user_or_role]
	     └─ Sets which user or role is mentioned when enough votes against a user are rea...
	  sc.vk [user] [server]
	     └─ Places your vote to have the passed user kicked.
	  sc.vkanon [yes_no]
	     └─ Sets whether vote messages are removed after voting (bot-admin only; always o...
	  sc.vkchannel 
	     └─ Gets which channel then mention posts to when enough votes against a user are...
	  sc.vkclear [user]
	     └─ Clears the votes against the passed user (bot-admin only).
	  sc.vkexpiretime [the_time]
	     └─ Sets the amount of time before a vote expires.  0 or less will make them perm...
	  sc.vkinfo 
	     └─ Lists the vote-kick info.
	  sc.vkmention 
	     └─ Gets which user or role is mentioned when enough votes against a user are rea...
	  sc.vkmutetime [the_time]
	     └─ Sets the number of time a user is muted when the mute votes are reached - 0 o...
	  sc.vks [user]
	     └─ Lists the vote count of the passed user (bot-admin only) or the author if no ...
	  sc.vktomention [number_of_votes]
	     └─ Sets the number of votes before the selected role or user is mentioned.  Anyt...
	  sc.vktomute [number_of_votes]
	     └─ Sets the number of votes before a user is muted.  Anything less than 1 will d...

## WatchURL
####	WatchURL Cog (7 commands) - WatchURL.py Extension:
	  sc.addwatchurl [url]
	     └─ Adds a new URL to watch for (bot-admin only).
	  sc.clearwatchedurls 
	     └─ Clears all URLs to watch for (bot-admin only).
	  sc.clearwatchurlmatches 
	     └─ Clears all URL watch list matches (bot-admin only).
	  sc.delwatchurl [url]
	     └─ Removes a URL from the watch list (bot-admin only).
	  sc.lasturls 
	     └─ Shows up to the last 200 URLs sent that matched the URL watch lists in order ...
	  sc.listwatchurls 
	     └─ Lists the URLs to watch for in passed messages.
	  sc.watchboturls [yes_no]
	     └─ Sets whether we watch for URLs from other bots (bot-admin only - disabled by ...

## Welcome
####	Welcome Cog (7 commands) - Welcome.py Extension:
	  sc.rawgoodbye [member]
	     └─ Prints the current goodbye message's markdown (bot-admin only).
	  sc.rawwelcome [member]
	     └─ Prints the current welcome message's markdown (bot-admin only).
	  sc.setgoodbye [message]
	     └─ Sets the goodbye message for your server (bot-admin only).
	  sc.setwelcome [message]
	     └─ Sets the welcome message for your server (bot-admin only). 
	  sc.setwelcomechannel [channel]
	     └─ Sets the channel for the welcome and goodbye messages (bot-admin only).
	  sc.testgoodbye [member]
	     └─ Prints the current goodbye message (bot-admin only).
	  sc.testwelcome [member]
	     └─ Prints the current welcome message (bot-admin only).

## Wiki
####	Wiki Cog (1 command) - Wiki.py Extension:
	  sc.wiki [search]
	     └─ Search Wikipedia!