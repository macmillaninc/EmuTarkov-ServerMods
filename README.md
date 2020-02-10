# EmuTarkov-ServerMods
A repository containing mods made for the EmuTarkov-Server

## **```/!\ IMPORTANT /!\```**
- **THIS REPOSITORY IS NOT A MOD**
- **YOU NEED TO PICK MODS INCLUDED IN THE DIFFERENTS FOLDER OF THE REPOSITORY**

## How to install a mod ?

1. Add the desired mod folder into ```/user/mods/```
2. Add this code in ```/user/server.config.json```:
```json
{
    "name": "Name of the Mod",
    "author": "Author of the mod",
    "version": "Mod version",
    "enabled": true
}
```
and replace
- ```Name of the Mod``` with the name of the desired mod
- ```Author of the mod``` with the name of the author from the desired mod
- ```Mod version``` with the version of the desired mod (found in mod.config.json inside the mod folder)

3. The server will automaticaly recache
4. Start the server & the game

## Note:
The Author name is the first part of the folder name<br>
The name of the mod, is the second part of the folder name<br>
eg : TheMaoci-EnableMultiplayerMod<br>
TheMaoci is the author, EnableMultiplayerMod is the name<br>

# Official links
**Discord link**: https://discord.gg/JnJEev4

**Reddit page**: https://www.reddit.com/r/EmuTarkov/