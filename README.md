# › Features
- Support for various databases in asynchronous: SQLite, H2, PostgreSQL, MariaDB, and MySQL
- Compatibility with language configurations
- Support for over 25 different gift spawn locations
- Customizable gift items using HeadDatabase ID's or Nicknames
- Customizable rewards, including commands, experience, and money rewards

# › Abilities:
- Limit on the number of gifts that can be collected
- Automatic saving of statistics at a specified interval (in minutes)
- Restrictions on the use of gifts in editing mode: prohibiting breaking, dropping, moving, and crafting

# › Commands
| Command | Description | Permission |
| --- | --- | --- |
| gifts | Help by commands | lightgifts.help
| gifts stats | Show your statistics | lightgifts.stats (default: true)
| gifts stats <player> | Show player statistics | lightgifts.stats.other
| gifts editor | Enable editing mode | lightgifts.editor
| gifts spawn <x, y, z> | Spawn a gift at specified coordinates | lightgifts.spawn.location
| gifts spawn | Spawn a gift from configuration | lightgifts.spawn
| gifts reset | Delete all gifts | lightgifts.reset
| gifts reload | Reload configs | lightgifts.reload
  
# › Permissions
| Permissions | Description
| --- | --- |
| lightcheck.bypass | Removes all prohibitions
| lightcheck.notify | For update alerts when logging in
| lightcheck.admin | Full access to the plugin
  
# › Placeholders (PAPi)
- %lightgifts_pickuped% - Number of gifts found
- %lightgifts_pickuped_%player_name% or %lightgifts_pickuped_kainlight% - The number of player's gifts found
- %lightgifts_total% - Number of gifts found with limit value
- %lightgifts_total_%player_name% or %lightgifts_total_kainlight% - The number of player's gifts found with limit value
