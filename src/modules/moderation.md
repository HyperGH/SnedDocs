# Moderation

---

## Setup and Configuration

To start setting up the moderation module, head to the dashboard, and navigate to **Modules > Moderation**. Here, you can configure:
- Which roles have access to moderation commands (these roles are also exempt from any auto-moderation, if set)
- Configure which role will be added to users when they are muted. This role should not have 'Send Messages' permissions
- Decide if users should be DM-d by the bot during punishment procedure, notifying them of it.
- If you want moderation commands to be removed from the chat

**Please note that without a mute role set, muting will not work!**

---

## Auto-Moderation

Sned is equipped with powerful auto-moderation features, which you can access by navigating to **Modules > Moderation > Auto-Moderation**. Here you will be able to decide what action the bot should take in case of certain pre-defined infractions. By default all auto-moderation capabilites are **disabled**.

You also have the ability to select which roles will be excluded from auto-moderation, although please note that roles with moderation permissions are automatically excluded, along with server administrators and owners.

One of the unique features of Sned is the "Smart" punishment type, which tries preemptively warning the user, before punishing them. The flow looks something like this:

1. User posts problematic content
2. Bot removes it and notifies the user
3. If the user keeps up the malicious behaviour within a certain timeframe, they will be formally warned, increasing their warning counter.
4. If the user still keeps going, then the punishment in the "Smart punishment type" option on the Dashboard will be used against the user.

---

## Commands

Below you will find all the moderation commands, and a brief description of each of them. For detailed command usage, you can  type `sn help <command_name>` in any of the channels where the bot is present.

| Command  | Description  |
| ------------ | ------------ |
| `sn kick <user>`  | Kicks a user from the server.  |
| `sn softban <user>`  | Bans a user from the server, then immediately unbans them. Useful for cleaning up messages from a user.   |
| `sn tempban <user> <duration>`  | Temporarily bans a user for the specified duration.  |
| `sn ban <user>`  | Bans a user from the server.  |
| `sn unban <user>`  | Unbans a user from the server.  |
| `sn mute <user>`  | Permanently mutes a user.  |
| `sn tempmute <user> <duration>`  | Temporarily mutes a user.  |
| `sn warn <user>`  | Warns a user, which increases their warn-count. (This can be viewed with `sn whois`)  |
| `sn warn clear <user>`  | Clear warnings for a user.  |
| `sn clear [count]`  | Clean up the bot's own messages in the channel. Optionally specify a number of messages.  |
| `sn purge [count] [user]`  | Bulk-delete messages from a channel, optionally specify the number of messages and a user to filter to.  |