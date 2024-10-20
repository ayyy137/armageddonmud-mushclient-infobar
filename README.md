# Armageddon MUSHclient Infobar

A [MUSHclient](http://www.gammon.com.au/mushclient/) infobar plugin designed for [Armageddon MUD](http://armageddon.org/).

### INSTALLATION INSTRUCTIONS ###

Step 1: Save this XML file and move it into the MUSHclient/Worlds/Plugins directory. Make sure it gets saved as XML and not plain text! Windows users may need to change the file type to "All Files" if "XML Document" is not already selected. If you get an error about saving in Program Files, feel free to save it in your documents folder or anywhere convenient.

Step 2: Load the plugin!
* Open MUSHclient
* Open the plugins menu (SHIFT+CONTROL+P)
* Click the "Add" button.
* Navigate to where you saved this file and select it.
* Close the plugins menu.

Step 3: Log into your Armageddon character and send the install command: InstallInfobar, then try the other commands: ManaOn, ManaOff, and SwapInfobar. These are all case sensitive.

Note: Your in game prompt values will no longer show in your logs. If you want that then you'll need to modify that value in the gag triggers in the plugin file.

### INFOBAR COMMANDS ###

* ManaOn - adds mana into your infobar
* ManaOff - hides mana from your infobar
* InstallInfobar - fixes your prompt after you die and make a new character
* SwapInfobar - swaps between the Detailed and Descriptive versions...
    Detailed is the default that's pictured at the top of this post. It offers a detailed list of numbers.
    Descriptive replaces the stat numbers with text that shows up when you drop below 65%. It looks like this:
        "You're hurting, exhausted, woozy, armed, mounted, and set for running. Also you're Fighting: Amos. It's late afternoon."

### UPDATE HISTORY ###

Version 3.3 (Jan 2022)
Add encumbrance and improve legibility and compactness.

Version 3.2 (September 2021)
Adds support for focus points - you will need to remove the existing version then re-run the installation steps below.

Version 3.1
New optional plugins for highlighting which are now defunct because the game has its own now.

Version 3.0:
Plugin installation
Open Source
One minute installation
Two different display options
Mana toggle
Font support in Linux

### UPDATE / UNINSTALL INSTRUCTIONS ###

Updating it as a plugin
* Go to plugins menu. Select it. Click Remove. Repeat installation process.

Uninstalling it as a plugin
* Go to the plugins menu. Select it. Click Remove.
* Fix your prompt to whatever you want. See the prompt help file for details.

### CREDITS ###

Originally a vbs script shared by Delirium, this was converted into Lua by Agent\_137 and lightly modified over the years with the help of testers RogueGunslinger, Prodikus, Iiyola, and others.

## Discussion ##
For support, you can create an issue in this repo or post in Armageddon's discord or this dedicated [MUSHclient infobar thread](https://gdb.armageddon.org/index.php/topic,34979.msg439267.htm).
