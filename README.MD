## Bukkit

- **spawn-limits:**
`monsters:50, animals:8, water-animals:7, water-ambient:10, ambient:1`

- **chunk-gc.period-in-ticks:** `400`

- **ticks-per.(type)-spawns:**
`monster:5, water:11, water-ambient:21, ambient:31`

- **autosave:** `6000`

## Spigot

- **save-user-cache-on-stop-only:** `true`

- **max-tick-time:**
`tile:1000, entity:1000`

- **mob-spawn-range:** 6
Def: 8
Impact: N/A

- **entity-activation-range:**
`animals:16, monsters:24, raiders: 48, misc:8`
Impact: Medium

- **tick-inactive-villagers:** false
Def: true
Impact: Medium

- **merge-radius:**
Def: item:2.5, exp:3.0
Opt: item:4.0, exp:6.0
Impact: Medium

- **nerf-spawner-mobs:** true
Def: false
Impact: Medium

- **item-despawn-rate:** 3000
Def: 6000 (5 minutes)
Impact: Situational

- **arrow-despawn-rate:** 300
Def: 1200
Impact: Minor

## Paper

- **max-auto-save-chunks-per-tick:** 6
Default: 24
Performance Impact: Heavy

- **optimize-explosions:** true
Default: false
Impact: Minor

mob-spawner-tick-rate
Def: 1
Opt: 2
Impact: Minor

disable-chest-cat-detection
Def: false
Opt: true
Impact: Minor

container-update-tick-rate
Def: 1
Opt: 3
Impact: Minor

max-entity-collisions (in Spigot.yml in some builds)
Def: 8
Opt: 2
Impact: Medium

grass-spread-tick-rate
Def: 1
Opt: 4
Impact: Medium

despawn-ranges
Def: soft: 32, hard: 128
Opt: soft: 28, hard: 96
Impact: Minor

hopper.disable-move-event
Def: false
Opt: true
Impact: Heavy

➫ This will significantly reduce hopper lag by preventing InventoryMoveItemEvent being called for EVERY slot in a container.

Warning: Plugins that listen for InventoryMoveItemEvent will break.

non-player-arrow-despawn-rate
Def: -1 (uses Spigot arrow-despawn-rate)
Opt: 60 (3 seconds)
Impact: Minor

creative-arrow-despawn-rate
Def: -1 (Spigot arrow-despawn-rate)
Opt: 60 (3 seconds)
Impact: Minor

prevent-moving-into-unloaded-chunks
Def: false
Opt: true
Impact: Medium

use-faster-eigencraft-redstone
Def: false
Opt: true
Impact: Heavy

armor-stands-tick
Def: true
Opt: false
Impact: Minor

per-player-mob-spawns
Def: false
Opt: true
Impact: Minor

alt-item-despawn-rate
Def: false
Opt: true
Impact: Medium

no-tick-view-distance
Def: -1
Opt: # > view-distance setting
Impact: N/A

anti-xray.enabled
Def: false
Opt: true
Impact: N/A