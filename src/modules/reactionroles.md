# Reaction Roles

--- 

## Usage

Reaction roles are used to simplify self-assigning roles to users, for example to gain access to certain channels, or to let users pick their username's color. To get started with creating reaction roles, simply use the command `sn rr create` (short for `reactionrole`) to start the interactive setup. Follow the setup instructions the bot provides to finish creating your reaction role. To manage reaction roles, type `sn rr`, this will list all reaction roles for the server, starting with their ID, then their channel, lastly the role they are set to give out. To delete and invalidate a reactionrole, type `sn rr del <ID>` where ID is the ID you got from listing the reaction roles.

## Commands

Below you will find all the commands related to reaction roles, and a brief description of each of them. For detailed command usage, you can  type `sn help <command_name>` in any of the channels where the bot is present.

| Command  | Description  |
| ------------ | ------------ |
| `sn reactionrole`  | Lists all reaction roles for the server, in an `ID-Channel-Role` format.   |
| `sn reactionrole add/create`  | Starts the interactive setup process for creating a new reaction-role.   |
| `sn reactionrole delete`  | Removes a reaction role and invalidates it. Does not delete the message associated, even if it was created by the bot.  |

