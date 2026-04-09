# Nexus Bot
[![License](http://img.shields.io/:license-mit-blue.svg)](http://doge.mit-license.org)  
Discord separates into text and voice channels, with no option to create a combined channel.  
The purpose of this bot is to create a text channel, which is visible only to those who are connected to the linked voice channel.  
Each time the last user leaves the voice channel, all non-pinned messages in the linked text channel will be deleted.  
**Want to use it on your server?** You can [self-host](https://github.com/andretkachenko/nexus-bot/wiki/How-to-host-it-youself) it.  

## How to use
You don't need to set up anything - once you join a voice channel (excluding inactive channels), a new category with the linked text channel will be created.  
Each time a user joins/leaves the voice channel, they will get/lose rights to see the linked text channel.  
Feel free to rename/move categories and text channels as you wish - it will not affect the bot.  
When the last user leaves the voice channel, messages in the linked text channel will be deleted (excluding pinned messages).  

For existing commands, either check [wiki](https://github.com/andretkachenko/nexus-bot/wiki/Existing-commands) or use the bot's slash commands on your server.  
