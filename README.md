# GuardChunk
Protect your server from lag and chunk overload by automatically limiting blocks and entities. GuardChunk keeps your performance stable, optimized, and secure.



# 🛡 GuardChunk

**GuardChunk** is a lightweight and highly configurable anti-lag plugin designed to prevent server performance issues before they happen.

Instead of clearing entities every few minutes, GuardChunk limits lag-causing blocks and entities **per chunk**, helping server owners maintain excellent TPS while giving players complete freedom to build.

Perfect for:

- Survival
- SkyBlock
- Prison
- OP Survival
- SMP
- Economy Servers

---

# ✨ Features

## ⚡ Prevent Lag Before It Happens

GuardChunk focuses on **prevention**, not cleanup.

Instead of deleting hundreds of entities every few minutes, it simply prevents chunks from exceeding configurable limits.

This results in:

✔ Better TPS

✔ Less server lag

✔ Better player experience

✔ Lower CPU usage

---

## 📦 Block Limits

Limit almost any block per chunk.

Examples:

- Hoppers

- Spawners

- Chests

- Barrels

- Furnaces

- Redstone

- Pistons

- Observers

- Armor Stands

- Item Frames

- Beacons

- Rails

- Composters

- And much more.

Every limit is fully configurable.

---

## 👾 Entity Limits

Prevent farms from creating excessive lag.

Supports:

- Zombies

- Skeletons

- Creepers

- Villagers

- Animals

- Minecarts

- Boats

- TNT

- Experience Orbs

- Dropped Items

- And every Minecraft entity.

---

## ⚙ Fully Configurable

Everything can be customized.

config.yml

- Enable or disable the plugin

- Warning percentage

- Debug mode

- Block limits

- Entity limits

- Custom messages

No coding required.

---

## 💬 Custom Messages

Every message can be edited.

Examples:

- Limit reached

- Warnings

- No permission

- Chunk information

- Help menu

Supports Minecraft color codes.

---

## 🧠 Smart Chunk Monitoring

Each chunk is monitored independently.

Every limit applies only to the current chunk.

This prevents players from abusing lag machines without affecting the rest of the world.

---

# 📂 Configuration

All settings are located in:

plugins/GuardChunk/config.yml

Example:

```yaml
HOPPER: 10

SPAWNER: 1

CHEST: 20

VILLAGER: 20

ITEM: 50
```

Setting a value to **-1** disables the limit.

Example:

```yaml
HOPPER: -1
```

Unlimited Hoppers.

---

# 🛠 Commands

| Command | Description |
|---------|-------------|
| /cg info | Shows information about the current chunk |
| /cg check | Checks another chunk |
| /cg listar | Displays all configured limits |
| /cg setlimite | Changes a limit without editing config.yml |
| /cg mensajes | Shows editable messages |
| /cg recargar | Reloads the configuration |
| /cg resetear | Clears chunk cache |
| /cg ayuda | Shows help |

---

# 📋 Supported Blocks

Examples include:

- Hoppers
- Spawners
- Chests
- Furnaces
- Barrels
- Redstone
- Pistons
- Sticky Pistons
- Observers
- Repeaters
- Comparators
- Item Frames
- Glow Item Frames
- Armor Stands
- Beacons
- Rails
- Bells
- Composters
- Bee Hives

Simply use the official Minecraft Material name.

Example:

```yaml
HOPPER: 10

CHEST: 20

SPAWNER: 1
```

---

# 👾 Supported Entities

Supports any Bukkit EntityType.

Examples:

Zombie

Skeleton

Creeper

Villager

Cow

Pig

Sheep

Minecart

Boat

Item

Experience Orb

TNT

Arrow

Falling Block

Simply add or modify the entity inside the configuration.

Example:

```yaml
ZOMBIE: 10

VILLAGER: 20

ITEM: 50
```

---

# 🚀 Performance

GuardChunk was built to be lightweight.

✔ Low memory usage

✔ Fast chunk scanning

✔ Optimized listeners

✔ No scheduled entity clearing

✔ Minimal CPU impact

---

# 📦 Compatibility

Minecraft:

- 1.15+

Servers:

- Paper

- Spigot

- Purpur

---

# ❤️ Why GuardChunk?

Unlike traditional anti-lag plugins that periodically remove entities and frustrate players, GuardChunk prevents lag from occurring by enforcing configurable per-chunk limits.

This creates a smoother gameplay experience while keeping your server optimized at all times.

---

Developed by **Jorge123987**
