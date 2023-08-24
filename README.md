# Cordevall for Lua
### The open-source simple-to-use Discord bot comes to Lua!
Cordevall for Lua takes programming in

For more bots in different programming languages, go to: https://github.com/Eveeifyeve/DiscordBots

## How to Install Cordevall for Lua
#### Step 1:
Go to the releases of Cordevall for Lua and install the most recent version.

#### Step  2:
Go to http://github.com/rjpcomputing/luaforwindows/releases

#### Step  3:
Download the most recent version (the .exe file) and open it.

#### Step  4:
Go through the installer and click Finish (optional: If you are a beginner, before you click 'Finish', click the 'Run a simple introduction' checkbox. It will open an introduction on how to use Lua.)

### Before you begin, you must install Luvit and Discordia as they aren't pre-installed into Lua for Windows.

#### Step 5:
Go to http://luvit.io and follow the instructions provided for your platform

#### Step 6:
To install Discordia, run ```lit install SinisterRectus/discordia```

#### Step 7:
Run your bot script using, for example, ```luvit bot.lua```

### Example from Discordia
```
local discordia = require('discordia')
local client = discordia.Client()

client:on('ready', function()
	print('Logged in as '.. client.user.username)
end)

client:on('messageCreate', function(message)
	if message.content == '!ping' then
		message.channel:send('Pong!')
	end
end)

client:run('Bot INSERT_TOKEN_HERE')
```
Now you can begin using Cordevall to program your dream Discord bot!

# Credits:
#### Cordevall was created by Eveeifyeve
#### Cordevall for Lua was created by StarryTheSuperstar
