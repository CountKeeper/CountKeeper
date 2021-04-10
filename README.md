A Discord bot that displays how many members have a given role by updating voice channels

Commands:
- create --- Creates a counting channel that tracks a role --- Takes a name for the channel and a role(pinged) as arguments
- edit --- Edits what role a counting channel tracks -- Takes the current name or ID of the channel, a role(pinged) and a new name as arguments
- prefix --- Changes the prefix of the bot for your server --- Takes a new prefix as an argument
- help --- Gives you a list of all the commands the bot suports
- several debugging command that print stuff to the console

You can make a channel track the people without any roles or make it track @everyone by providing "norole" and "everyone" as an argument instead of a pinged role

Using a command without providing any arguments will cause the bot to tell you more about that command

Pinging the bot will make it tell you its prefix for your server


TODO:
- Website
- More advanced tracking commands
- Control panel for configuring the bot


CONTRIBUTING:
- Push your changes to the beta branch, so I can test them on the beta version of the bot. Please don't override the databases or config.json in the process :). They have caused me much grief...
-----------------------------------------------------------------------

Self hosting instructions:

Requirements:
1. Stable internet
2. 24/7 online pc (or at least while you are using the bot)
3. Python installed


Linux/MacOS:

1. clone the main branch of the repo (git clone https://github.com/CountKeeper/CountKeeper.git) or (git clone git@github.com:CountKeeper/CountKeeper.git)
2. cd CountKeeper
3. pip install -r requirements.txt
4. Open config.json and change BOT_TOKEN to you bot token. You must create a discord app and then a bot for this. Instructions can be found in your search engine of choice. I won't list them here since the steps might change in the future. Search terms are "How to create discord bot" or "Bot token discord"
5. run start.sh

Windows:
1. clone the main branch of the repo (git clone https://github.com/CountKeeper/CountKeeper.git) or (git clone git@github.com:CountKeeper/CountKeeper.git)
2. cd CountKeeper
3. pip install -r requirements.txt
4. Open config.json and change BOT_TOKEN to you bot token. You must create a discord app and then a bot for this. Instructions can be found in your search engine of choice. I won't list them here since the steps might change in the future. Search terms are "How to create discord bot" or "Bot token discord"
5. run start.bat

----------------------------------------------------------------------

Invite link for the bot:
https://discord.com/oauth2/authorize?client_id=813180967028129842&scope=bot&permissions=16

Support server:
https://discord.gg/fq3kYsK4Ms
