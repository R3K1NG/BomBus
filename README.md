# [BOMBUSMOD](https://telegram.me/AnonySECURITY)

**An advanced and powerful administration bot based on NEW TG-CLI


* * *

## Commands

| Use help |
|:--------|:------------|
| [#!/]help | just send help in your group and get the commands |

**You can use "#", "!", or "/" to begin all commands

* * *

# Installation

```sh
# Let's install the bot.
cd $HOME
git clone https://github.com/goblinor/BomBus.git
cd BomBus
chmod +x BomBus.sh
./BomBus.sh install
./BomBus.sh # Enter a phone number & confirmation code.
بعد از کد دادن و سودو کردن خودتون
که باید خودتون رو در فایل config
سودو کنید
بعد با این دستور ربات رو افلاین کنید
cd BomBus
killall screen
برای روشن کردن
screen ./BomBus.sh
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/goblinor/BomBus.git && cd BomBus && chmod +x BomBus.sh && ./BomBus.sh install && ./BomBus.sh
```

* * *

### Sudo And Bot
After you run the bot for first time, send it `!id`. Get your ID and stop the bot.

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    133362226,
    0,
    YourID
  }
```
add your bot ID at line 4 in bot.lua
add your ID in config.lua
add your ID at line 362 in tools.lua
Then restart the bot.

# Support and development

More information anonysecurity Development](https://telegram.me/anonysecurity)

# Developers!

[sc0rpion tn](https://github.com/Goblinor) ([Telegram](https://telegram.me/sc0rpion))

