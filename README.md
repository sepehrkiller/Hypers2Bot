# Hypers2Bot

A simple telegram Hyper bot Based on LUA
You should have [lua](http://www.lua.org/) installed

# Installation

open Teminal and then

```bash
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev

sudo apt-get install lua-socket & sudo apt-get install lua-sec
```


Clone the bot

```
git clone https://github.com/sepehrkiller/Hypers2Bot.git
cd Hypers2Bot

```

then config bot in Hypers2Bot.lua

```lua

local bot_api_key = "Your Token Here" -- token
local BASE_URL = "https://api.telegram.org/bot"..bot_api_key
local BASE_FOLDER = "" -- do not set this
```

And enter your telegram-id in admins table in [Hypers2Bot.lua](https://github.com/sepehrkiller/Hypers2Bot/blob/master/Hypers2Bot.lua#L19)
```lua
local var = false
  local admins = {111222333}-- put your id here
  for k,v in pairs(admins) do

```

Save Hypers2Bot.lua

```
bash launch.sh install && bash launch.sh
``` 

# Warning

CopyRight 2016 (C)
Made On Lua
Based On GNU LICENSE

Created By : [SepehrKiller](https://telegram.me/sepehrkiller)
Enjoy !
