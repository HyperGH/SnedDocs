# Tags

--- 

## Usage

Tags offer users an easy way to save important messages, frequently asked questions, or funny content, then retrieve them later by simply calling the tag by it's name.

#### Creation

To create a tag, type `sn tag create <name> <content>`. If you wish to add spaces to the name of the tag, please put the name in quotation marks. The maxmimum length for tags is currently **1500** characters. To call your tag, type `sn tag <tagname>`. This will display the contents of the tag in the current channel. 

#### Management and Moderation

To edit your tag, type `sn tag edit <tagname> <new content>`. Please note that you can only edit your own tags. If you wish to transfer ownership of your tag, you can type `sn tag transfer <tagname> <new owner>`. This transfers all ownership and related permissions to the new owner. As a moderator, you can also transfer anyone's tag to any other user, including yourself. Deleting tags is done via the `sn tag delete <tagname>` if you own the tag, or if you are a moderator. If you would like to know more about a tag, type `sn tag info <tagname>`. This will display information such as the tag's current owner, aliases, if any.

#### Discovery

To find new tags, you can either use `sn tag search <name>`, which will attempt to find a tag with a given name or alias (aliases are marked with *italic*.) or list all the tags in the server by using `sn tag list`, which will spawn a paginated list of all the tags in the server.

For some advanced features, see the full command list below.

## Permissions

Permissions in this category are controlled via the `tags` permission-node. `moderation` implicitly inherits this node. For more information about permissions, please see [Permissions](./permissions.md).

## Commands

Below you will find all the tag-related commands, and a brief description of each of them. For detailed command usage, you can  type `sn help <command_name>` in any of the channels where the bot is present.

| Command  | Description  |
| ------------ | ------------ |
| `sn tag <tagname or alias>`  | Calls a tag, displaying it's contents in the current channel.   |
| `sn tag claim <tagname or alias>`  | Claims a tag, transferring it's ownership to the invoker. Can only be used on abandoned tags, when the tag owner left the server.   |
| `sn tag create <tagname> <content>`  | Creates a new tag and binds it's ownership to the invoker.  |
| `sn tag edit <tagname or alias> <content>`  | Edits the specified tag's contents. Requires ownership of the tag.  |
| `sn tag alias <tagname> <alias>`  | Adds an alias to the tag, meaning that the tag can now be called from both names. Requires tag ownership. Cannot overlap with existing tagnames & aliases.  |
| `sn tag delalias <tagname> <alias>`  | Removes an alias from the tag, freeing it up for other tags to use as their name or alias. Requires tag ownership.  |
| `sn tag delete <tagname or alias>`  | Deletes a tag, freeing up the name for other tags or aliases. Requires tag ownership or access to moderation commands.  |
| `sn tag transfer <tagname or alias> <new owner>`  | Transfers a tag's ownership to a different user. Requires tag ownership or access to moderation commands.  |
| `sn tag list`  | Spawns a paginated list of all the tags for this server. Aliases are not listed.  |
| `sn tag search <query>`  | Searches for a given tag or alias. Aliases are formatted with *italic*.  |
| `sn tag info <tagname or alias>`  | Displays information about the tag, such as the current owner, and a list of aliases associated with the tag.  |

