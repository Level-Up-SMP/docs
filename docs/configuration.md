# Server Configuration

Contained herein is the more detailed information of the server configuration. If the configuration is noted here it is either considered an important configuration item or is has been changed from it's default.

## Configuration Options

### Command: Game Rules

| Option                         | Value   |
| ------------------------------ | ------- |
| `global_sound_events`          | `false` |
| `players_sleeping_percentage`  | `0`     |
| `spawn_phantoms`               | `false` |
| `max_snow_accumulation_height` | `0`     |

---

### File: server.properties

| Option                | Value  | Note              |
| --------------------- | ------ | ----------------- |
| `difficulty`          | `hard` |                   |
| `max-build-height`    | `320`  |                   |
| `max-world-size`      | `8000` | Subject to change |
| `pvp`                 | `true` |                   |
| `simulation-distance` | `6`    | Subject to change |
| `view-distance`       | `7`    | Subject to change |

---

### Plugin: Chunky Border

This plugin helps us keep the map sizes in check to prevent large diskspace usages + backups.

#### Dimenson Borders

| Dimension     | Radius |
| ------------- | ------ |
| world         | 8000   |
| world_nether  | 4000   |
| workd_the_end | 5000   |

---

### Plugin: WorldGuard

| Option                                  | Value  |
| --------------------------------------- | ------ |
| `regions`.`protect-against-liquid-flow` | `true` |
| `fire`.`disable-all-fire-spread`        | `true` |
| `mobs`.`block-creeper-block-damage`     | `true` |
| `mobs`.`anti-wolf-dumbness`             | `true` |
| `mobs`.`disable-enderman-griefing`      | `true` |
| `mobs`.`block-painting-destroy`         | `true` |
| `mobs`.`block-item-frame-destroy`       | `true` |
| `mobs`.`block-armor-stand-destroy`      | `true` |
| `crops`.`disable-creature-trampling`    | `true` |
| `crops`.`disable-player-trampling`      | `true` |
