# Hack Challenge 2
Please read though this whole page before starting.

This week you are tasked with creating a discord bot that can complete the following tasks:
- Make it so your bot only responds to your messages.
- Respond to the command `ping` with the response `pong` (You can add additional responses if you want).
- Write a command that takes a input string and reverses it. For example the command `reverse bob bill` would give the output `llib bob`.
- Write a command that displays the total number of users on the server and lists how many of them are bots.
- Calculate at what times of day the server is most active.

# Additional Task
- Write a command that gives the weather forecast for a given city (You'll want to look into weather API's)
- Write a command that allows you to bind text or images to some test. An example would be `create bob do the thing` whenever `bob` is typed into the chat the bot would now respond with `do the thing`. You should also have a way of deleting these.
- Write a command that returns the first image in google images for a given keyword (Make sure you are keeping things safe for work)

# Libraries to use
For this week we suggest working in node.js or Python. For node.js [discord.js](https://discord.js.org/#/) is one of the simplest libraries to use. For python [discord.py](https://github.com/Rapptz/discord.py) is a simple library for writing bots. Both libraries provide basic starting examples which would be a good idea to base your code of.

# Setting up your bot
1. Make sure you are logged into discord first
2. Head to https://discordapp.com/developers/applications/
3. Click create an application
4. Give your application whatever name you want (it will be renamed to bot-<your username> when it joins the server)
5. Click the bot section of the menu and hit the `Add Bot` button.
6. The user token listed there will be needed in your code. Check out the examples for the listed libraries to see where to put it.
7. Click the OAuth2 section and select `bot` from the list of scopes. Then copy the link it generates and DM it to a member of committee so that it can be added to the server.

# Rules for having bots on the swan_hack server
1. Your bot must only respond to your messages
2. Your bot has limited permissions setup so that it can read all channels but only send message in #sandbox. Committee reserve the right to change these permissions at any point.
3. Your bot will be treated as an extension of your user. Actions that violate the rules listed in #welcome and swan_hack's [code of conduct](https://swanhack.co.uk/code_of_conduct.pdf) will result in the removal of both your user and your bot from the server.
4. You may be asked by committee to change your bots behaviour so that it spams less (as an example) if you do not comply with this your bot will be removed from the server.
5. Any data collected by your bot should not be stored indefinitely. A recommendation of storing it for no more then 1 week is given.
