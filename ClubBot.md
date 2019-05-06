# BCCB User Manual

This is the official reference guide for the unofficial Bondage Club Chat bot (BCCB), developed and maintained by adokilume. For bug reports, suggestions, or general comments, feel free to message `adokilume#1553` on Discord.

The game [Bondage College / Bondage Club](https://github.com/Ben987/Bondage-College) was made by Ben987.

## Interacting with the Bot

In general, any interaction with the bot starts with giving it a command. Commands always start by saying the bot's name, followed by a comma, followed by a space, followed by the actual command. The bot will introduce itself by name whenever a new player enters the chat room. Assuming the bot's name is "ClubBot", a command will look like this:

`ClubBot, <your command here>`

(where `<your command here>` is replaced with one of the commands from the "Command Reference" section).

Note that it is possible to assign your own personal nickname to the bot with a certain command, in which case, it will react to both it's actual name and the nickname you gave it.

A command will only work if you don't post any other text before it in the same chat message. Most commands will work fine if you add additional text after them, such as punctiation, additional flavor, or even full sentences. The only exception to this is when a command is used to assign a name to someone/something, in which case all of the remaining message is considered to be the name.

Commands are case-insensitive (including the bot's name) unless otherwise stated.

## Command Reference

Remember to say the bot's name followed by a comma and a space before any of these commands, otherwise they won't work.

Commands listed next to each other (separated by a comma) are aliases and can be used interchangeably.

Anything written inside `<>` signifies that it should be replaced by a custom parameter of your choice.

Commands tagged with *NoSub* will, by default, only work for members whose **Dominant** reputation is higher than -50 (aka **Submissive** lower than 50). Commands tagged with *DomOnly* will only work for members whose **Dominant** reputation is at least 50.

### Basic Commands

`help`

Displays a randomly chosen hint about what you can do with the bot (obsolete with the release of this manual, may be removed in the future).

`ping`, `marco`

Each of these triggers a static, pre-defined response. Useful to check if the bot is still functional.

### Nickname / Role Assignment

`call me <name>`

Assigns a custom name for the bot to refer to you by. Note that `<name>` is semi case sensitive, in the sense that the bot will remember and use the capitalization you used in the command. Also note that this nickname cannot be used by other players to refer to you in other commands. If multiple nicknames are assigned by using this command repeatedly, one of them will be chosen at random every time the bot refers to you. If you want the bot to occasionally call you by your actual name as well, you will need to add it to the nickname list. It is currently not possible to remove nicknames.

`your name is now <name>`, `your name is <name>`, `you are an <name>`, `you are a <name>`, `your new name is <name>`, `i will call you <name>`

Will make `<name>` a new nickname you can now use to give commands to the bot. Nicknames are personal and will only work for the person who assigned them. Note that you can also keep calling the bot by its original name even after giving it a nickname, as it will react to both. `<name>` is case insensitive in the sense that it will work no matter what capitalization you use it in; however, when it's used by the bot itself, it will use the capitalization provided in the original command. Multiple nicknames can be assigned by using this command repeatedly.

`obey <name>`, `listen to <name>` *(DomOnly)*

If there is a member called `<name>`, this command will enable them to use any command tagged with *NoSub*, regardless of their reputation. There is currently no way to undo this command.

### Basic Actions

`kneel`, `sit`, `down`, `get on your knees`, `on your knees`, `know your place` *(NoSub)*

Will cause the bot to kneel down, as long as it's not kneeling already and it is able to do so.

`stand`, `up`, `rise`, `get up` *(NoSub)*

Will cause the bot to stand up, as long as it's not standing already and it is able to do so.

### Bondage Related Commands

`tie me up`

Will apply random rope bondage to the user (this will be expanded upon soon).

`gag me`

Will apply a random gag to the user (this will be expanded upon soon).

### Miscellaneous Commands

`rock`, `paper`, `scissors`

Will cause the bot to respond with "Rock", "Paper", or "Scissors" at random, along with a message stating if it won, lost or tied in accordance to the rules of the popular decision making game.

### Secret Commands

Nope, not telling. You can figure these ones out on your own. ;)

## FAQ

**Where/When/How do I meet the bot?**

Since it's still rather bare-bones at the time of writing, the bot will only be active occasionally in a private chat room in the game (usually called "BotTest", which is subject to change). Keep an eye out in the game's discord server for announcements on when it's available for testing. Eventually, there might be a dedicated public room on a semi-regular basis. Unfortunately, it cannot be available 24/7 at the moment since the bot requires an actual account to be logged into Bondage Club in order to run.

**Will you release the bot's source code?**

For the time being, no, sorry. Making the code available publicly could lead to potentially harmful abuse, trolling, or identity theft. I may change my mind about this eventually, depending on how the game and its community evolve. In theory, anyone with sufficient JavaScript knowledge could easily build their own bot anyway. But for now, just to keep it safe, I will only consider giving out the code to people I trust enough to use it responsibly.

## Changelog

* **2019-05-06:** Support for multiple nicknames as well as a basic `gag me` command.
* **2019-05-02:** Initial release of this manual, bot supports basic commands such as kneeling, tying volunteers in basic rope bondage, and nickname usage.
