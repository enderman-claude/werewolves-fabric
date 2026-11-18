# Werewolves — Fabric port (Minecraft 1.16.5)

> **Migration progress: 0%.** Nothing has been ported yet. This repository currently contains the unmodified Forge source of Werewolves, plus this README.

This is an unofficial Fabric port of **Werewolves** by TeamLapen (Cheaterpaul and contributors). It is **not** the original project and is not affiliated with or endorsed by its authors.

## Original project

- Source: https://github.com/TeamLapen/Werewolves (branch `1.16`)
- Please check out the original repository for the real, supported mod.
- Werewolves depends on Vampirism. The Vampirism port is at https://github.com/enderman-claude/vampirism-fabric (0% migrated). This port will depend on that one, not the original Vampirism.

## Licence

- Licensed under the **GNU Lesser General Public License v3.0** (see `LICENSE`), as in the original.
- Original copyright and licence notices are kept. Changes made in this port will be marked as such.

## Version note

The source in this repository is version **1.0.4** (`gradle.properties`), while the jar the port was started from is **1.1.0.3**. Differences between the two are not yet checked.

## Milestones

Each milestone needs to be tested in a Fabric dev client by the maintainer before it is ticked. Fabric API is the only intended dependency, plus the Fabric Vampirism port once it exists.

- [ ] **M0 — Scaffold:** Fabric Loom project for 1.16.5, builds and launches with no mod content.
- [ ] **M1 — Vampirism dependency:** link against the Fabric Vampirism port (blocked until Vampirism reaches its core milestones).
- [ ] **M2 — Registries and event bus:** items, entities, and effects registered through Fabric; Forge event subscriptions replaced (about 192 Java files in total across the mod).
- [ ] **M3 — Capabilities:** Forge capabilities replaced with Fabric attachments or a custom equivalent.
- [ ] **M4 — Networking:** Forge packets replaced with Fabric networking.
- [ ] **M5 — Configuration:** `ForgeConfigSpec` replaced.
- [ ] **M6 — Rendering and client:** werewolf models, renderers, and GUIs ported.
- [ ] **M7 — Data and assets:** recipes, loot tables, tags, and models in place.
- [ ] **M8 — Werewolf core:** transformation and main werewolf abilities working.
- [ ] **M9 — Remaining features:** everything not covered above.

## Status log

- 2026-11-18: Repository created from the 1.16 branch of upstream. No code changes yet.
