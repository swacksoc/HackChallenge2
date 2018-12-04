# Hack Challenge 2
Please read though this whole page before starting.

This week you are tasked with creating a discord bot that can complete the following tasks:
- Make it so your bot only responds to your messages.
- Respond to the command `ping` with the response `pong` (You can add additional responses if you want).
- Write a command that takes a input string and reverses it. For example the command `reverse bob bill` would give the output `llib bob`.
- Write a command that displays the total number of users on the server and lists how many of them are bots.
- Calculate at what times of day the server is most active.

# Libraries to use
For this week we suggest working in node.js or Python. For node.js [discord.js](https://discord.js.org/#/) is one of the simplest libraries to use. For python [discord.py](https://github.com/Rapptz/discord.py) is a simple library for writing bots. Both libraries provide basic starting examples which would be a good idea to base your code of.

# Setting up your bot
1. Make sure you are logged into discord first
2. From the swan_hack discord server run the command `!join_role sandbox` in any channel
3. Head to https://discordapp.com/developers/applications/
4. Click create an application
5. Give your application whatever name you want (it will be renamed to bot-<your username> when it joins the server)
6. Click the bot section of the menu and hit the `Add Bot` button.
7. The user token listed there will be needed in your code. Check out the examples for the listed libraries to see where to put it.
8. Click the OAuth2 section and select `bot` from the list of scopes. Then copy the link it generates and DM it to @unreturnable#0001 or another member of committee so that it can be added to the server.

# Rules for having bots on the swan_hack server
1. Your bot must only respond to your messages
2. Your bot has limited permissions setup so that it can read all channels but only send message in #sandbox. Committee reserve the right to change these permissions at any point.
3. Your bot will be treated as an extension of your user. Actions that violate the rules listed in #welcome and swan_hack's [code of conduct](https://swanhack.co.uk/code_of_conduct.pdf) will result in the removal of both your user and your bot from the server.
4. You may be asked by committee to change your bots behaviour so that it spams less (as an example) if you do not comply with this your bot will be removed from the server.
5. Any data collected by your bot should not be stored indefinitely. A recommendation of storing it for no more then 1 week is given.
