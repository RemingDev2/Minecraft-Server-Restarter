# Auto Restart Minecraft Server

[![My Skills](https://skillicons.dev/icons?i=py,github,idea&theme=light)](https://skillicons.dev)

# Goal
This file allows you to restart your Minecraft server (hosted locally), if it stops.

MODS DO IT WELL, WITHOUT CONFIGURATION BUT I DID IT BEFORE FOUND MODS

## Setup
**Place it in the root of the server**

  1. Open [auto_run.py](auto_run.py) in a code/text editor

  2. Change {command} to the server command. --> Open **run.sh** or **run.bat** and Copy-Paste the last line (java @user_jvm...)

  3. Run your server once, stop it and get the last line, without the useless information | [15:56:18] [Server thread/INFO] [minecraft/MinecraftServer]: ThreadedAnvilChunkStorage: All dimensions are saved --> **All dimensions are saved**

  4. Change {text_line} to the previously retrieved line

  5. Open [config_file.py](config_file.py). Modify {text_line} by the line recovered previously and launch it.

  6. In 'auto-run.py' change {number} to the number previously displayed.

Your files are ready. All you have to do is launch [auto_run.py](auto_run.py) !
