# Events

---

Events are a way to organize meetings or playsessions inside Discord. Users can sign up to multiple custom-created categories, and upon creation, category member-caps, roles required to sign up, and more can be customized. To get started with events, type `sn event create`, which will start an interactive setup to create an event. Once done, users can sign up to events via the buttons provided by the bot, and once the event timer runs out, those who signed up will be notified by the bot in the same channel. If you wish to cancel or delete an event, you can do so by first obtaining the ID of it, which you can either find in the footer of the event message, or retrieve via `sn events`, then delete it via `sn event del <ID>`.

## Permissions

Permissions in this category are controlled via the `events` permission-node. `moderation` implicitly inherits this node. For more information about permissions, please see [Permissions](./permissions.md).

## Commands

Below you will find all the event-related commands, and a brief description of each of them. For detailed command usage, you can type `sn help <command_name>` in any of the channels where the bot is present.

| Command  | Description  |
| ------------ | ------------ |
| `sn events`  | Shows all currently active events.   |
| `sn event create`  | Starts an interactive setup to create a new event.   |
| `sn event del <ID>`  | Deletes an event by ID.  |
