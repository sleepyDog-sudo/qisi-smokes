<div align="center">

# Qisi Smokes

### A Fabric 1.20.1 smoking / tobacco mod made for cozy survival servers.

![Minecraft](https://img.shields.io/badge/Minecraft-1.20.1-brightgreen?style=for-the-badge)
![Loader](https://img.shields.io/badge/Loader-Fabric-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Playable-orange?style=for-the-badge)

`qisi-smokes` adds tobacco crops, cigarette items, cigarette packs, smoking rules, and a client-side first-person smoking animation for a Homestead-style Minecraft server.

</div>

---

## What is this?

**Qisi Smokes** is a small survival-flavored Minecraft mod focused on cigarettes and tobacco progression.

It was made for a relaxed multiplayer survival setup, not for hardcore balance or competitive gameplay. The goal is to make smoking items feel like a small immersive system: grow tobacco, craft cigarettes, use packs, smoke with an animation, and deal with a daily limit.

---

## Features

- Tobacco crop system
- Cigarettes and burst capsule cigarettes
- Cigarette packs
- Cigarette butts
- Ashtray
- Two-block-tall vending machine
- Coffee / energy drink items
- Daily smoking limit
- Client-side first-person smoking animation addon
- Designed for the **Homestead** modpack environment

---

## Minecraft version

| Requirement | Version |
|---|---|
| Minecraft | `1.20.1` |
| Mod loader | `Fabric` |
| Target modpack | `Homestead` |

---

## Installation

### Client

Put **both** files into your Minecraft client `mods` folder:

```txt
qisi-smokes-fabric-0.1.6.jar
qisi-smokes-anim-addon-0.3.1.jar
```

The animation addon is required only if you want the first-person smoking animation.

---

### Server

Put **only** this file into the server `mods` folder:

```txt
qisi-smokes-fabric-0.1.6.jar
```

Do **not** install the animation addon on the server.

```txt
qisi-smokes-anim-addon-0.3.1.jar  <- client only
```

---

## Client / server split

| File | Client | Server | Notes |
|---|---:|---:|---|
| `qisi-smokes-fabric-0.1.6.jar` | Yes | Yes | Main gameplay mod |
| `qisi-smokes-anim-addon-0.3.1.jar` | Yes | No | First-person animation only |

If the animation addon is installed on the server, remove it. It is not needed server-side.

---

## Gameplay rules

- Cigarettes can be smoked in multiple puffs.
- Smoking progress is tracked per item use.
- The system includes a daily smoking limit.
- Sleeping resets the daily count.
- Going over the limit is intended to punish the player.

This is intentionally more of a survival roleplay mechanic than a pure utility item.

---

## Suggested server use

This mod is meant for a small private server with friends.

Recommended setup:

```txt
Minecraft 1.20.1
Fabric server
Homestead modpack
qisi-smokes main jar on both client and server
animation addon on client only
```

---

## Known notes

- The animation addon is client-only.
- The mod was built and tested around a specific Homestead server setup.
- Other modpacks may work, but are not the main target.
- Balance is tuned for casual survival play.

---

## Project status

```txt
Playable / personal server build
```

This project is still being adjusted through actual survival gameplay testing.

---

<div align="center">

### smoke -> test -> break -> fix -> repeat

</div>
