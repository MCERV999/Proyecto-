import discord
from discord.ext import commands
permisos = discord.Intents.default()
permisos.message_content = True
bot999 = commands.Bot(command_prefix="/", intents=permisos)
@bot999.event
async def on_ready():
    print("bot en linea / bot online / bot en ligne / 線上機器人 / 在线机器人")
@bot999.command()
async def hola(ctx):
    await ctx.send("hola , mucho gusto")
wally.run("")
# Proyecto-
