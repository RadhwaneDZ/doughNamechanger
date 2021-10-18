[![Discord][discord-shield]][discord-url]

## :pushpin: About this Script
![doughNamechanger-banner|512x256](https://dough.land/u/bor6xDKhil.png)

Simple Ui-based script for players to change name (firstname + lastname)

## :ledger: Requirements
* ESX (version shouldn't matter)
* Do not change the name of the resource if you do not know how to edit the rest of the files

## :clipboard: Installation
1. Drag and Drop `doughNamechanger` into your resources folder
2. Add `ensure doughNamechanger` to your server.cfg

## :file_folder: Important Files
### config.lua
Easily add more locations and change cost
```sh
Config.Cost = 5000
Config.Account = 'bank'
Config.EnableLogs = true

Config.EnableBlip = true
Config.BlipSprite = 480
Config.BlipColour = 17
Config.BlipScale = 0.65
Config.BlipLabel = 'Passport Agency'

Config.Locations = {
    vector3(297.9539, -592.4486, 43.2841)
}
```



[discord-shield]: https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white
[discord-url]: https://discord.gg/2MupXQMSWR
