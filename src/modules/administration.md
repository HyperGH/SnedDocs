# Administration

--- 

## Commands

Below you will find all the administration commands, and a brief description of each of them. For detailed command usage, you can  type `sn help <command_name>` in any of the channels where the bot is present.

| Command  | Description  |
| ------------ | ------------ |
| `sn prefix`  | Shows the bot's prefixes for this server. A server can have up to **5** custom prefixes.   |
| `sn prefix add <prefix>`  | Adds a custom prefix to the bot's list of prefixes. Please note that if this is your first custom prefix, it will disable the default one. (`sn `) You can manually re-add it.   |
| `sn prefix del <prefix>`  | Removes a prefix from the list of prefixes.  |
| `sn priviligedrole`  | [DEPRECATED] Shows all priviliged roles for the server. Deprecated in favour of more granular permission controls via the dashboard.  |
| `sn priviligedrole add <role>`  | [DEPRECATED] Adds a role to the list of roles that can use commands requiring priviliged access.  |
| `sn priviligedrole del <role>`  | [DEPRECATED] Removes a role from the list of priviliged roles.  |
| `sn resetsettings`  | Resets the bot's configuration for the server. Please note this also erases all timers, so temporarily banned users will stay banned.  |
| `sn setnick <nickname>`  | Sets the nickname of the bot for this server. Input `None` or `Null` to reset it.  |
| `sn sudo <command> [arguments]`  | Runs a command in sudo-mode, bypassing all cooldowns and checks.  |
| `sn whois <user>`  | Returns detailed information about the given user, even if they are not in the server.  |
