# QuoteBot
***
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com) [![Discord Channel](https://img.shields.io/discord/707835273081257984?style=for-the-badge)](https://discord.gg/sAbQMyF9) [![QuoteBot](https://img.shields.io/uptimerobot/status/m778918918-3e92c097147760ee39d02d36?style=for-the-badge)](https://discord.gg/sAbQMyF9)

### list of command
Command | Result
------------ | -------------
__$inspire__ | return random inspirational quote
__$list__ | return the list of save encouragement phrases
__$hello__ | greetings coming from a bot
__$new__ <string> | add new encouragement phrase
__$del__ <index> | delete encouragement phrase
__$responding__ <boolean>| will turn on or off the ability of bot responding to your random message 

To keep this bot running I used flask web server running in repl.it this will make my bot sleep after an hour without an activity.

To avoid this bot from stop running I decided to use uptimerobot to ping my web server every 5 minutes.
    