# BaseBot

# What is this?
BaseBot is a Discord bot made by SpaceX that is simple to use. Below is the instructions on how to install it. Once you download it, you are free to modify it and if you need any support, you may join this discord server. https://discord.gg/SAERSza

# How to install

<b> Windows </b>
You should type in command prompt
```
python3 -m pip install -U discord.py
```

<b> Linux </b>
Type in in console 
```pip install discord.py
```
# How to modify.

Simply go to
```
@client.event
async def on_message(message):
```
And Add:
```
if message.content.startswith(prefix + "commandname"):
  Do stuff
```