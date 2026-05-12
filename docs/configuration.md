# :notebook: Server Configuration

Contained herein is the more detailed information of the server configuration. If the configuration is noted here it is either considered an important configuration item or is has been changed from it's default.

## Configuration Options

### Command: Game Rules

| Option                         | Value   |
| ------------------------------ | ------- |
| `global_sound_events`          | `false` |
| `players_sleeping_percentage`  | `25`    |
| `spawn_phantoms`               | `false` |
| `max_snow_accumulation_height` | `0`     |

---

### File: config/paper-world-defaults.yml

#### Item Despawn Rates

Overrides the default 5-minute (6000-tick) item despawn rate for specific items via `alt-item-despawn-rate`. Junk items despawn faster to reduce ground clutter; valuable items linger longer so players have more time to recover them.

| Item                                    | Group                | Despawn |
| --------------------------------------- | -------------------- | ------- |
| `andesite`                              | Junk                 | 2 min   |
| `arrow`                                 | Junk                 | 2 min   |
| `bone`                                  | Junk                 | 2 min   |
| `bone_meal`                             | Junk                 | 2 min   |
| `cobbled_deepslate`                     | Junk                 | 2 min   |
| `cobblestone`                           | Junk                 | 2 min   |
| `diorite`                               | Junk                 | 2 min   |
| `dirt`                                  | Junk                 | 2 min   |
| `egg`                                   | Junk                 | 2 min   |
| `feather`                               | Junk                 | 2 min   |
| `flint`                                 | Junk                 | 2 min   |
| `glass_bottle`                          | Junk                 | 2 min   |
| `glow_ink_sac`                          | Junk                 | 2 min   |
| `gold_nugget`                           | Junk                 | 2 min   |
| `granite`                               | Junk                 | 2 min   |
| `gravel`                                | Junk                 | 2 min   |
| `gunpowder`                             | Junk                 | 2 min   |
| `ink_sac`                               | Junk                 | 2 min   |
| `melon_slice`                           | Junk                 | 2 min   |
| `netherrack`                            | Junk                 | 2 min   |
| `oak_leaves`                            | Junk                 | 2 min   |
| `oak_sapling`                           | Junk                 | 2 min   |
| `rotten_flesh`                          | Junk                 | 2 min   |
| `sand`                                  | Junk                 | 2 min   |
| `spider_eye`                            | Junk                 | 2 min   |
| `string`                                | Junk                 | 2 min   |
| `wheat_seeds`                           | Junk                 | 2 min   |
| `diamond_axe`                           | Diamond gear         | 10 min  |
| `diamond_boots`                         | Diamond gear         | 10 min  |
| `diamond_chestplate`                    | Diamond gear         | 10 min  |
| `diamond_helmet`                        | Diamond gear         | 10 min  |
| `diamond_hoe`                           | Diamond gear         | 10 min  |
| `diamond_leggings`                      | Diamond gear         | 10 min  |
| `diamond_pickaxe`                       | Diamond gear         | 10 min  |
| `diamond_shovel`                        | Diamond gear         | 10 min  |
| `diamond_sword`                         | Diamond gear         | 10 min  |
| `black_shulker_box`                     | Shulker boxes        | 10 min  |
| `blue_shulker_box`                      | Shulker boxes        | 10 min  |
| `brown_shulker_box`                     | Shulker boxes        | 10 min  |
| `cyan_shulker_box`                      | Shulker boxes        | 10 min  |
| `gray_shulker_box`                      | Shulker boxes        | 10 min  |
| `green_shulker_box`                     | Shulker boxes        | 10 min  |
| `light_blue_shulker_box`                | Shulker boxes        | 10 min  |
| `light_gray_shulker_box`                | Shulker boxes        | 10 min  |
| `lime_shulker_box`                      | Shulker boxes        | 10 min  |
| `magenta_shulker_box`                   | Shulker boxes        | 10 min  |
| `orange_shulker_box`                    | Shulker boxes        | 10 min  |
| `pink_shulker_box`                      | Shulker boxes        | 10 min  |
| `purple_shulker_box`                    | Shulker boxes        | 10 min  |
| `red_shulker_box`                       | Shulker boxes        | 10 min  |
| `shulker_box`                           | Shulker boxes        | 10 min  |
| `white_shulker_box`                     | Shulker boxes        | 10 min  |
| `yellow_shulker_box`                    | Shulker boxes        | 10 min  |
| `netherite_axe`                         | Netherite gear       | 20 min  |
| `netherite_boots`                       | Netherite gear       | 20 min  |
| `netherite_chestplate`                  | Netherite gear       | 20 min  |
| `netherite_helmet`                      | Netherite gear       | 20 min  |
| `netherite_hoe`                         | Netherite gear       | 20 min  |
| `netherite_leggings`                    | Netherite gear       | 20 min  |
| `netherite_pickaxe`                     | Netherite gear       | 20 min  |
| `netherite_shovel`                      | Netherite gear       | 20 min  |
| `netherite_sword`                       | Netherite gear       | 20 min  |
| `netherite_ingot`                       | Netherite materials  | 20 min  |
| `netherite_scrap`                       | Netherite materials  | 20 min  |
| `netherite_upgrade_smithing_template`   | Netherite materials  | 20 min  |
| `elytra`                                | High-value items     | 20 min  |
| `player_head`                           | High-value items     | 20 min  |
| `totem_of_undying`                      | High-value items     | 20 min  |
| `bolt_armor_trim_smithing_template`     | Armor trim templates | 20 min  |
| `coast_armor_trim_smithing_template`    | Armor trim templates | 20 min  |
| `dune_armor_trim_smithing_template`     | Armor trim templates | 20 min  |
| `eye_armor_trim_smithing_template`      | Armor trim templates | 20 min  |
| `flow_armor_trim_smithing_template`     | Armor trim templates | 20 min  |
| `host_armor_trim_smithing_template`     | Armor trim templates | 20 min  |
| `raiser_armor_trim_smithing_template`   | Armor trim templates | 20 min  |
| `rib_armor_trim_smithing_template`      | Armor trim templates | 20 min  |
| `sentry_armor_trim_smithing_template`   | Armor trim templates | 20 min  |
| `shaper_armor_trim_smithing_template`   | Armor trim templates | 20 min  |
| `silence_armor_trim_smithing_template`  | Armor trim templates | 20 min  |
| `snout_armor_trim_smithing_template`    | Armor trim templates | 20 min  |
| `spire_armor_trim_smithing_template`    | Armor trim templates | 20 min  |
| `tide_armor_trim_smithing_template`     | Armor trim templates | 20 min  |
| `vex_armor_trim_smithing_template`      | Armor trim templates | 20 min  |
| `ward_armor_trim_smithing_template`     | Armor trim templates | 20 min  |
| `wayfinder_armor_trim_smithing_template`| Armor trim templates | 20 min  |
| `wild_armor_trim_smithing_template`     | Armor trim templates | 20 min  |

#### Other Settings

| Option                                              | Value               |
| --------------------------------------------------- | ------------------- |
| `chunks`.`prevent-moving-into-unloaded-chunks`      | `true`              |
| `collisions`.`max-entity-collisions`                | `2`                 |
| `entities`.`behavior`.`disable-chest-cat-detection` | `true`              |
| `environment`.`generate-flat-bedrock`               | `true`              |
| `lootables`.`auto-replenish`                        | `true`              |
| `lootables`.`refresh-max`                           | `12h`               |
| `lootables`.`refresh-min`                           | `8h`                |
| `lootables`.`restrict-player-reloot-time`           | `1d`                |
| `misc`.`redstone-implementation`                    | `ALTERNATE_CURRENT` |

---

### File: server.properties

| Option                | Value   | Note              |
| --------------------- | ------- | ----------------- |
| `difficulty`          | `hard`  |                   |
| `max-build-height`    | `320`   |                   |
| `max-world-size`      | `10000` |                   |
| `pvp`                 | `true`  |                   |
| `simulation-distance` | `6`     | Subject to change |
| `view-distance`       | `7`     | Subject to change |

---

### Plugin: Chunky Border

This plugin helps us keep the map sizes in check to prevent large diskspace usages + backups.

#### Dimension Borders

| Dimension      | Radius |
| -------------- | ------ |
| world          | 10000  |
| world_admin    | 500    |
| world_creative | 500    |
| world_nether   | 4000   |
| world_resource | 2000   |
| world_the_end  | 5000   |

---

### Plugin: EssentialsX

| Option                          | Value   |
| ------------------------------- | ------- |
| `auto-afk-timeout`              | `28800` |
| `force-disable-teleport-safety` | `true`  |
| `teleport-cooldown`             | `3`     |
| `teleport-delay`                | `3`     |
| `unsafe-enchantments`           | `true`  |

---

### Plugin: WorldGuard

| Option                                     | Value  |
| ------------------------------------------ | ------ |
| `crops`.`disable-creature-trampling`       | `true` |
| `crops`.`disable-player-trampling`         | `true` |
| `fire`.`disable-all-fire-spread`           | `true` |
| `fire`.`disable-lava-fire-spread`          | `true` |
| `mobs`.`anti-wolf-dumbness`                | `true` |
| `mobs`.`block-armor-stand-destroy`         | `true` |
| `mobs`.`block-creeper-block-damage`        | `true` |
| `mobs`.`block-item-frame-destroy`          | `true` |
| `mobs`.`block-painting-destroy`            | `true` |
| `mobs`.`block-wither-block-damage`         | `true` |
| `mobs`.`block-wither-skull-block-damage`   | `true` |
| `mobs`.`disable-enderman-griefing`         | `true` |
| `regions`.`nether-portal-protection`       | `true` |
| `regions`.`protect-against-liquid-flow`    | `true` |
| `sniffer-egg`.`disable-creature-trampling` | `true` |
| `sniffer-egg`.`disable-player-trampling`   | `true` |
| `turtle-egg`.`disable-creature-trampling`  | `true` |
| `turtle-egg`.`disable-player-trampling`    | `true` |
