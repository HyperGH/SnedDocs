# Reminders

--- 

## Usage

Reminders offer users the ability to set and manage... well... reminders! You can create a reminder by typing `sn remindme <when and what>`.

## Time-formatting

#### Relative

| Short  | Long  |
| ------------ | ------------ |
| `s`  | `sec` or `second(s)` |
| `m`  | `min` or `minute(s)` |
| `h`  | `hour(s)` |
| `d`  | `day(s)` |
| `w`  | `week(s)` |
| `M`  | `month(s)` |
| `Y`  | `year(s)` |

#### Absolute

`YYYY-MM-dd hh-mm`
`YYYY-MM-dd`

*Please note that absolute timezones __must__ be in UTC!*

#### Examples

 - `sn remindme in 2 hours to go to sleep`
 - `sn remind 5d example`
 - `sn reminder 2021-04-03 12:35 test`

 #### Managing reminders

 To list all your currently pending reminders, type `sn reminders`. This will list all your current reminders, their ID, their due-date, and a sneak-peek of their content. To cancel a reminder, type `delreminder <ID>`, with the ID being the ID you obtained from listing your reminders.

## Commands

Below you will find all reminder related commands, and a brief description of each of them. For detailed command usage, you can type `sn help <command_name>` in any of the channels where the bot is present.

| Command  | Description  |
| ------------ | ------------ |
| `sn reminder <text to parse>`  | Parses the input text for timestamps, and creates a reminder upon finding them. Sends the reminder in the invoking channel, if that fails, falls back to DM-ing the user.   |
| `sn reminders`  | Lists all pending reminders for the invoking user, showing their ID, due-date, and a snapshot of their contents.   |
| `sn delreminder <ID>`  | Cancels a reminder by ID.  |
