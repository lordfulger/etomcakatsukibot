# etoakatsukibot

[![GitHub release]
[![Python] 
[![Discord](https://discordapp.com/api/guilds/372001222858768394/widget.json?style=shield)](https://discord.gg/bots)


etoakatsukibot is the official Discord music bot written for [Python](https://www.python.org "Python homepage") 3.5+, using the [discord.py](https://github.com/lordfulger/discord.py) library. It plays requested songs, from YouTube and other services, into a Discord server (or multiple servers) and if the queue becomes empty it will play through a list of existing songs, if configured to do so. The bot features a permissions system allowing owners to restrict commands to certain people. As well as playing songs, etoakatsukibot is capable of streaming live media into a voice channel (experimental).

![Main](https://i.imgur.com/EZljY52.png)

## Setup
Setting up the etoakatsukibot is relatively painless - just follow one of the [guides](https://just-some-bots.github.io/MusicBot/) we have created for you. After that, you can begin to configure your bot to ensure that it can connect to Discord.

The main configuration file is `config/options.ini`, but is not included. Simply make a copy of `example_options.ini` and rename to `options.ini`. See `example_options.ini` for more information on how to configure it.

### Commands

There are many commands that can be used with the bot. Most notably, the `play <url>` command (preceded by your command prefix) will download, process, and play a song from YouTube or a similar site. A full list of commands are available [here](https://just-some-bots.github.io/MusicBot/#guidescommands "Commands").

### Further reading

* [Support Discord server](https://discord.gg/bots)
* [Project license](LICENSE)
