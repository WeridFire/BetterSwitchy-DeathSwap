# BetterSwitchy-DeathSwap
A minecraft Skirpt plugin to play DeathSwap in 2+ players. Fully Customizable with kits, magicitems and made throught GUI!

# Setup

The plugin requires skRayFall (https://sk.rayfall.net/) and skBee (https://www.spigotmc.org/resources/skbee-skript-addon.75839/) addons wich you can download freely. To install theese two addons just drag them in the plugin folder.

To install betterswitchy, download this repo, open the plugin folder of your minecraft server, serach for the "Skript" folder, open the "scripts" folder and just drag the "betterswitchy.sk" file in. (Note: the plugin is written in Skript so you need to have Skript Latest version on your server)

# User commands
To give users access to the following commands you need them to have "switchy.user" permission.

The command identifier here is "/switchy" with aliases: "/sw", "/swtch": 
	
	"/sw join [GameName]" : makes you join game [GameName]
	"/sw games" : opens a GUI to join games
	"/sw hub" : teleport player to hub
	"/sw quit" : make player quit the game
	"/sw showkit [KitName]" : opens a gui to see a kit
	"/sw kits" : opens a gui to see all kits
	"/sw help" : if you need help with commands in game
      
# Admin commands:
 To give admins access to the following commands you need them to have "switchy.admin" permission.
 
 The command identifier here is "/adminswitchy" with aliases: "/asw", "/aswtch":
 
	"/asw create [GameName]" : creates a new game
	"/asw start [GameName]" : starts a new game
	"/asw delete [GameName]" : delete an existing game
	"/asw kit [kitName] [player]" : give a kit to a player
	"/asw savekit [kitName]" : saves your inventory as a kit named <kitName>
	"/asw delkit [kitName]" : delete an existing kit
	"/asw setsymbol" : sets a symbol for the kit to be displayed in "/sw kits"
	"/asw sethub" : sets the hub where all players will be teleported after the game
	"/asw format" : restore every option to default value (it will ask for confirmation)
	"/asw setoption [GameName] [OptionName] [Value]" : set a custom game option for your game
	"/asw help" : if you need help with commands in game
      
Valid options are: gametime, min_player, max_player, countdown. (Note: all times are in seconds!!!)

# Custom Items commands
 To give admins access to the following commands you need them to have "switchy.admin" permission.
 
 The command identifier here is "/itemswitchy" with aliases: "/isw", "/iswtch":
 
 	"/isw give [MagicItem] [Player]": gives [Player] a [MagicItem]
 
 Valid magic items are: jumper, switcher, mushroom_of_power.
 
 
