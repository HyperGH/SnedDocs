# Permissions

---

 ## Configuration

 Permissions should be one of the first things one should configure after adding the bot to a new server. This can be done via the `sn permisson` (or `perm` for a shortened alias) command. This will show you the current configuration of the permissions on the server. Permissions are divided up into **permission-nodes**, and a list of roles can be assigned to any given node. To do this, the command `sn perm add <node> <role>` can be used. It is also a good idea to check the information page of a permission-node via the `sn perm info <node>`, although they are also listed below for convenience. Lastly, to remove a role from a node, use `sn perm del <node> <role>`.

 ### Permission-nodes

 These are all the permission-nodes at your disposal:

 | Node  | Description  |
| ------------ | ------------ |
| `moderation`  | Allows control of all moderation commands. Also excluded from auto-moderation. Includes the following nodes automatically: `automod_exclusions`, `tags`, `giveaways`, `fun`, `events`.  |
| `automod_exclusions`  | Excludes roles from auto-moderation. For more granular control please see the dashboard.   |
| `administrator`  | Allows total control over the bot, with all commands. Also excludes from auto-moderation. This is a dangerous permission to grant.  |
| `tags`  | Allows creation & basic management of tags. Users with `moderation` get additional permissions. |
| `role_buttons`  | Allows creation and management of role-buttons. This may be a dangerous permission to grant as it can be exploited to gain roles.  |
| `giveaways`  | Allows creation and management of giveaways. This permission node is not necessary to enter them.  |
| `fun`  | Allows usage of commands in the `Fun` category.  |
| `events`  | Allows creation and management of events. This permission node is not necessary to sign up for them.  |

## Permissions

Permissions in this category are controlled via the `administrator` permission-node. This means to initially set up permissions, you will have to be a Discord **administrator** or **server owner**.

## Commands

Below you will find all the commands related to permissions, and a brief description of each of them. For detailed command usage, you can type `sn help <command_name>` in any of the channels where the bot is present.


| Command  | Description  |
| ------------ | ------------ |
| `sn permissions`  | Lists the current status of all the permission-nodes.   |
| `sn permission add <node> <role>`  | Adds a role to a permission-node.   |
| `sn permission del <node> <role>`  | Removes a role from a permission-node.  |
| `sn permission info <node>`  | Show information about a permission-node.  |