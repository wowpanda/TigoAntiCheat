# FiveM AntiCheat by Tigo

[![Thymon](https://i.imgur.com/3EquTNl.jpg)](https://www.tigodev.com)

[![Developer](https://img.shields.io/badge/Developer-TigoDevelopment-darkgreen)](https://github.com/TigoDevelopment)
[![Discord](https://img.shields.io/badge/Discord-Tigo%239999-purple)](https://github.com/TigoDevelopment/FiveM-AntiCheat)
[![Version](https://img.shields.io/badge/Version-0.0.1-darkgreen)](https://github.com/TigoDevelopment/FiveM-AntiCheat)
[![Version](https://img.shields.io/badge/License-MIT-darkgreen)](https://github.com/TigoDevelopment/FiveM-AntiCheat)

### About TigoAntiCheat

AntiCheat by Tigo is a resource created for FiveM. This resource is to detect hackers and ban them from your server.

### Requirement
- None

### Get Started
In order to use this anticheat, all `esx:`, `esx_` etc. must be renamed.
The anticheat replaces `esx_...` server calls to perm bans.

Change e.g. `esx_drugs` to `tac_drugs` (only `EventHandlers`, `ClientEvents` and `ServerEvents`, leave resource folder just the orignal resource name example: `esx_drugs`).

[![Edit ESX](https://i.imgur.com/JwMIDdN.png)](https://i.imgur.com/JwMIDdN.png)

### Enable `/anticheat` for players
If you want `/anticheat` command available for example your Admin's than you can add this line to your `server.cfg`
```cfg
add_ace group.admin tigoanticheat.commands allow
```
Console is always allowed to execute `/anticheat` command.
Use `/anticheat` or `/anticheat help` to show all available commands.

### 

### License
MIT

### Disclamer
---
This resource was created by me with all the knowledge at the time of writing. It doesn't mean cheating becomes impossible. Updates will be done if there is time and reason to do so. The request of new functionality is allowed, but does not mean that it will be released.