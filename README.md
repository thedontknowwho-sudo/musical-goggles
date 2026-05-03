# Not Your Friend — Minecraft Fabric Mod (1.20.1)

A standalone horror mod featuring **the Mimic** — a creature that disguises itself as a nearby player and stalks them silently, until it can't hold back any longer.

---

## 🕵️ What is the Mimic?

The **Mimic** is a mob that:

1. **Picks a player target** on spawn and disguises itself to look like them
2. **Follows quietly** — staying just close enough to be noticed, performing player-like actions (sneaking, strafing, looking around, arm swinging)
3. **Watches you** — if you stare at it for too long, its suspicion meter fills up
4. **Reveals itself** — with a dramatic bone-cracking sound sequence and lights flickering off
5. **Hunts you** — in its true form it is invulnerable, fast, and wants you dead

---

## 📦 Dependencies

Install these before using:

- [Fabric Loader](https://fabricmc.net/use/) ≥ 0.15.11
- [Fabric API](https://modrinth.com/mod/fabric-api) for Minecraft 1.20.1
- [GeckoLib](https://modrinth.com/mod/geckolib) 4.4.9 for 1.20.1

---

## 🛠️ How to Build

```bash
./gradlew build
```

The output `.jar` will be in `build/libs/`.

---

## 🎮 Spawning the Mimic

The Mimic does not spawn naturally by default. Use a spawn egg or the `/summon` command:

```
/summon not-your-friend:mimic
```

---

## 📜 Credits & License

This mod was adapted from **SPB-Revamped** by **SpacePotato** (YouTube: @SpacePotatoee),
which is licensed under [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html).

Original source: https://github.com/SpacePotato/MinecraftFoundFootage

This mod is also licensed under **GPL-3.0**. You are free to modify and redistribute it,
provided you keep the same license and give credit.

---

## 🔊 Assets

All sounds, textures, animations, and 3D models are from the original SPB-Revamped project
and are used under the terms of the GPL-3.0 license.
