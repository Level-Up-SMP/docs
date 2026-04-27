# Status Plugin

Level Up SMP employs a status plugin called StatusX that is written and maintained by MDW.

## Commands

| Command | Description |
| ------- | ----------- |
| `/status clear` | Clear your status |
| `/status help` | View the help menu |
| `/status list [availabilities\|statuses]` | Get a list of statuses and availabilities |
| `/status nosleep` | Toggle the no-sleep prompt |
| `/status set <status> <availability>` | Set your status |
| `/status view <username>` | View another player's status |

## Status Indicator

The status indicator is a small box next to a player's name made up of two halves. The left half represents the player's current status, and the right half represents their availability. You can find this status indicator in the TAB menu.

### Statuses

| Color | Status | Description |
| ----- | ------ | ----------- |
| Grey | None | No status set |
| Red | Busy | Busy with something else |
| Yellow | Multitasking | Splitting attention between the game and other things |
| Purple | Streaming | Currently streaming content |
| Pink | Recording | Currently recording content |
| Green | Playing | Just playing the game |

### Availabilities

| Color | Availability | Description |
| ----- | ------------ | ----------- |
| Grey | None | No availability set |
| Green | Open | Open to collaboration |
| Yellow | Ask First | Ask this player first |
| Red | Do Not Disturb | Does not want to be disturbed |

## No Sleep

The plugin also lets players signal that they do not want others to sleep through the night. Running `/status nosleep` toggles this on, and whenever another player enters a bed, a message will appear letting them know you'd prefer they don't sleep.
