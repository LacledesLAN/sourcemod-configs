# sourcemod_config

No matter what game or operating system, there are some config files and plugins we need to be common among all source engine game files among all game servers. All of these are config files or platform agnostic plugins or libraries. All of the following files are platform agnostic (works with windows or linux) and will be applied on top of the platform specific config.

Sourcemod configs files

/addons/sourcemod/configs

admins_simple.ini
This file contains steam ids of all admins. This file is essentially the reason why the system would allow certian people to use admin commands and some benefits. 
https://wiki.alliedmods.net/Adding_Admins_(SourceMod)#Simple_Admins

core.cfg
This file is a config file that configures the core of sourcemod. Generally this file is unmodified with the exception of the "MinidumpAccount" line for the accelerator plugin. 


/addons/sourcemod/plugins

logconnections-ll.smx
This is a modification of player 1's log conenctions plugin. It simply records players connects and disconnects.  The only modifcation is that the log file is put with the other log files instead of its own directory.
https://forums.alliedmods.net/showthread.php?p=1845362

serverstatus-ll.smx
This plugin does a quick diagnostic of the server and posts to the console "Sourcemod is running". This is used mostly to for development and testing.
https://forums.alliedmods.net/showthread.php?t=294826

Updater.smx
A simple plugin that allows for plugin developers to have plugins updated automatically. 
https://forums.alliedmods.net/showthread.php?p=1570806

/cfg/

sourcemod.cfg
Another config file for sourcemod, the options on here allow the configureation of base plugins like reservedslots, voting, and chat flood protection. Its stock with the exception of "sm_cvar sv_hibernate_when_empty 0" to prevent hibernation. 


Extensions
These are files that are required by many plugins 

SMLIB
SMLib is a collection of over 300 function stocks for sourcemod written by the basic principle that every line of code should only exist one time.
https://forums.alliedmods.net/showthread.php?t=148387
https://github.com/bcserv/smlib/

Socket
Provide extra networking functionality to sourcemod scripts and plugins
https://forums.alliedmods.net/showthread.php?t=67640

Steamworks
This plugin allows steamworks functions to sourcepwn. 
https://forums.alliedmods.net/showthread.php?t=229556
https://github.com/KyleSanderson/SteamWorks

