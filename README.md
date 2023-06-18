[![Watch the video](https://img.youtube.com/vi/1zbs7K46cpg/maxresdefault.jpg)](https://youtu.be/1zbs7K46cpg)
# JAVA 16 or Higher
## DEPENDENCIES: [NBTAPI](https://github.com/tr7zw/Item-NBT-API/releases), [PLACEHOLDERAPI](https://github.com/PlaceholderAPI/PlaceholderAPI/releases)
## SOFT: [Vault](https://github.com/MilkBowl/Vault/releases), [PlayerPoints](https://www.spigotmc.org/resources/80745/), [TokenManager](https://github.com/Realizedd/TokenManager/releases), [HeadDatabase](https://www.spigotmc.org/resources/14280/)
# › Features
- Support for various databases in asynchronous: SQLite, H2, PostgreSQL, MariaDB, and MySQL
- Spawn gifts at several specified locations
- Customizable gift items using HeadDatabase ID's or Nicknames
- Customizable rewards: using events (exp, money[vault,playerpoints,tokenmanager], sound, effect, drop, message, broadcast, command
- Multiple languages (more in the future)

# › Abilities:
- Limit on the number of gifts that can be collected (Raising the level when the limit is reached)
- Automatic saving of statistics at a specified interval (in minutes)
- Restrictions on the use of gifts in editing mode: prohibiting breaking, dropping, moving, and crafting
- Randomization gift skins and reward amounts

# › Commands
| Command | Description | Permission |
| --- | --- | --- |
| gifts | Help by commands | lightgifts.help
| gifts stats rewards | Rewards menu | lightgifts.rewards
| gifts stats <set|add|remove> count | Managing the number of collected gifts | lightgifts.stats.<set|add|remove>.count
| gifts stats <set|add|remove> level | Managing the level of statistics | lightgifts.stats.<set|add|remove>.level
| gifts stats | Show your statistics | lightgifts.stats
| gifts stats <player> | Show player statistics | lightgifts.stats.other
| gifts editor | Enable editing mode | lightgifts.editor
| gifts spawn <x, y, z> | Spawn a gift at specified coordinates | lightgifts.spawn.location
| gifts spawn | Spawn a gift from configuration | lightgifts.spawn
| gifts reset <gifts or statistics> | Delete all gifts | lightgifts.reset
| gifts reload | Reload configs | lightgifts.reload
| gifts reload | If the config has been updated, you can easily update it too without deleting it | lightgifts.reload
  
# › Permissions
| Permissions | Description
| --- | --- |
| lightgifts.bypass | Removes all prohibitions
| lightgifts.notify | For update alerts when logging in
| lightgifts.admin | Full access to the plugin
  
# › Placeholders (PAPi)
- %lightgifts_pickuped% - Number of gifts found
- %lightgifts_pickuped_NICKNAME% - The number of player's gifts found
- %lightgifts_total% - Number of gifts found with limit value
- %lightgifts_total_NICKNAME% - The number of player's gifts found with limit value
