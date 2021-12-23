# darthoce.github.io

A example of a discord bot

```py
import discord
from discord.ext import commands

client = commands.Bot(command_prefix="")
client.remove_command("help")
token = ""

client.run(token)
```
