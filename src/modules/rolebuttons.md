# Role-Buttons

--- 

## Usage

Role-buttons are used to simplify self-assigning roles to users, for example to gain access to certain channels, or to let users pick their username's color. To get started with creating role-buttons, simply use the command `sn rb create` (short for `rolebutton`) to start the interactive setup. Follow the setup instructions the bot provides to finish creating your role-button. To manage role-buttons, type `sn rb`, this will list all role-buttons for the server, starting with their ID, then their channel, lastly the role they are set to give out. To delete a role-button, type `sn rb del <ID>` where ID is the ID you got from listing the role-buttons. There is a maximum limit of **10** role-buttons per message, and **200** per server.

## Permissions

Permissions in this category are controlled via the `role_buttons` permission-node. For more information about permissions, please see [Permissions](./permissions.md).

## Commands

Below you will find all the commands related to role-buttons, and a brief description of each of them. For detailed command usage, you can type `sn help <command_name>` in any of the channels where the bot is present.

| Command  | Description  |
| ------------ | ------------ |
| `sn rolebutton`  | Lists all role-buttons for the server, in an `ID-Channel-Role` format.   |
| `sn rolebutton add/create`  | Starts the interactive setup process for creating a new role-button.   |
| `sn rolebutton delete/del`  | Removes a role-button. Does not delete the message associated.  |

