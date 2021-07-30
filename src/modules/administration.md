# Administration

--- 

## Permissions

Permissions in this category are controlled via the `administrator` permission-node. For more information about permissions, please see [Permissions](./permissions.md).

## Commands

Below you will find all the administration commands, and a brief description of each of them. For detailed command usage, you can type `sn help <command_name>` in any of the channels where the bot is present.

| Command  | Description  |
| ------------ | ------------ |
| `sn prefix`  | Shows the bot's prefixes for this server. A server can have up to **5** custom prefixes.   |
| `sn prefix add <prefix>`  | Adds a custom prefix to the bot's list of prefixes. Please note that if this is your first custom prefix, it will disable the default one. (`sn `) You can manually re-add it.   |
| `sn prefix del <prefix>`  | Removes a prefix from the list of prefixes.  |
| `sn resetsettings`  | Resets the bot's configuration for the server. Please note this also erases all timers, so temporarily banned users will stay banned.  |
| `sn setnick <nickname>`  | Sets the nickname of the bot for this server. Input `None` or `Null` to reset it.  |
| `sn sudo <command> [arguments]`  | Runs a command in sudo-mode, bypassing all cooldowns and checks.  |
