# Giveaways

--- 

## Usage

Giveaways are way for users to give away prizes to members of the server. To create a giveaway, type `sn giveaway create`. This will start an interactive setup, simply follow the instructions to finish creating the giveaway. To list all running giveaways, simply type `sn giveaway list`, which will show all running giveaways, their ID, channel, and the prize. If you would like to pre-maturely end a giveaway, type `sn giveaway end <ID>`. If you want to cancel a giveaway completely without calculating a winner, type `sn giveaway cancel <ID>`.

## Permissions

Permissions in this category are controlled via the `giveaways` permission-node. `moderation` implicitly inherits this node. For more information about permissions, please see [Permissions](./permissions.md).

## Commands

Below you will find all giveaway related commands, and a brief description of each of them. For detailed command usage, you can type `sn help <command_name>` in any of the channels where the bot is present.

| Command  | Description  |
| ------------ | ------------ |
| `sn giveaway create`  | Starts the interactive setup process for creating a new giveaway.   |
| `sn giveaway list`  | Lists all running giveaways for the server.   |
| `sn giveaway end <ID>`  | Ends the given giveaway early, calculating the winners.  |
| `sn giveaway cancel <ID>`  | Ends the given giveaway early, without calculating any winners. |