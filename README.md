# EmuTarkov-ServerMods
A repository containing mods made for the EmuTarkov-Server

/!\ **THIS REPOSITORY IS NOT A MOD YOU NEED TO PICK MODS INCLUDED IN THE DIFFERENTS FOLDER OF THE REPOSITORY IT ONLY CONTAINS COMMUNITY MADE MODS** /!\

# How to install a mod ?

1. Add the desired mod folder into /user/mods
2. Add this code in /user/server.config.json :
```json
{
    "name": "Name of the Mod",
    "author": "Author of the mod",
    "version": "1.0",
    "enabled": true
}
```
3. The server will automaticaly recache
4. Start the server & the game

## Note : 
The name of the mod, is the second part of the folder name<br>
The Author name is the first part of the folder name<br>
eg : SenkoSan-EnableLanMod<br>
SenkoSan is the author, EnableLandMod is the name<br>
