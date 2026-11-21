# Prisma by Purrline Rocketworks [![License: MIT](https://img.shields.io/badge/code-MIT-yellow.svg)](LICENSE) [![License: CC BY 4.0](https://img.shields.io/badge/art-CC%20BY%204.0-lightgrey.svg)](LICENSE-ART)

A two-stage small satellite launcher for [Kitten Space Agency](https://ahwoo.com/app/100000/kitten-space-agency), from the fictional rocket maker Purrline Rocketworks. Inspired by Spectrum from Isar Aerospace.

## Compatibility

Validated against KSA build version **2026.11.16.5901**.

[![Watch the Prisma launch video](https://img.youtube.com/vi/jkoOCArH9X4/maxresdefault.jpg)](https://youtu.be/jkoOCArH9X4)

*The launch video, made in the game with these mods.*

![Prisma on the pad](images/listing/pad-hero.jpg)

## Parts

| Picture | Part | What it is |
| --- | --- | --- |
| ![Fairing Half 2 m Medium](images/parts/PrismaFairingA_Prefab_FairingHalf.jpg) ![Fairing Half 2 m Medium (B)](images/parts/PrismaFairingA_Prefab_FairingHalfB.jpg) | **Fairing Half 2 m Medium** | Fairing half, 6.10 m long; place two; white or black carbon |
| ![Fairing Base 2 m](images/parts/PrismaFairingA_Prefab_FairingBase.jpg) | **Fairing Base 2 m** | Fairing base ring with the 1 m payload adapter |
| ![Prisma Payload Mass Simulator (1 t)](images/parts/PrismaPayloadA_Prefab_MassSimulator.jpg) | **Prisma Payload Mass Simulator (1 t)** | 1000 kg dummy payload for test flights |
| ![Prisma Stage 2](images/parts/PrismaUpperA_Prefab_Stage2.jpg) | **Prisma Stage 2** | Upper-stage tank with four RCS blocks and switchable avionics. Fits the Altair Vac. |
| ![Prisma Interstage](images/parts/PrismaTankA_Prefab_Interstage.jpg) | **Prisma Interstage** | Interstage with its own decoupler; the Altair Vac sits inside |
| ![Prisma Stage 1 Tank](images/parts/PrismaTankA_Prefab_Stage1Tank.jpg) | **Prisma Stage 1 Tank** | The 2 m first stage tank |
| ![Altair Engine Bay](images/parts/AltairEngineA_Prefab_EngineBay.jpg) | **Altair Engine Bay** | Nine Altair engines, each with its own gimbal and its own engine controller |
| ![Altair](images/parts/AltairEngineA_Prefab_Altair.jpg) | **Altair** | Single sea level engine |
| ![Altair Vac](images/parts/AltairEngineA_Prefab_AltairVac.jpg) | **Altair Vac** | Single vacuum engine with the long nozzle |
| ![Prisma Hold-down Ring](images/parts/PrismaGroundA_Prefab_HoldDownRing.jpg) | **Prisma Hold-down Ring** | Holds the rocket on the pad and releases at lift-off |
| ![Prisma Strongback](images/parts/PrismaGroundA_Prefab_Strongback.jpg) | **Prisma Strongback** | Tower beside the rocket; stays on the pad |

The fairing is the 2 m fairing of [Fairings by Purrline Rocketworks](https://github.com/Maximilian-Nesslauer/KSA-PurrlineFairings), which also has 3 m fairings and hammerhead bases. Prisma contains the 2 m fairing, so you do not need Fairings for it. Press V on a placed half to change between white and black carbon.

All parts on one sheet: [images/parts/all-parts.jpg](images/parts/all-parts.jpg)

The rocket is about 28 m tall. Sizes and texture density follow the stock parts, so Prisma mixes with stock tanks and engines. The engines burn liquid oxygen and propane.

Prisma Stage 2 avionics draw 15 W. Use the power switch and status light to manage the 400 kJ battery, which can power the avionics alone for about 7 hours. The avionics have a radiation tolerance of 100 Gy, an upset dose of 90 mSv and 1 g/cm2 of shielding.

The gimbals on Altair and the nine engines in the Altair Engine Bay can slew at up to 10 degrees per second. Altair Vac can slew at up to 4 degrees per second.

Altair and the engines in the Altair Engine Bay can leave a faint stock plume trail during atmospheric burns. Enable **Plume trails** in the game's graphics settings to see it.

The editor prevents new surface attachments to the jettisonable fairing halves. Attach payloads to the fairing base or to the stage.

![The engine bay](images/listing/engine-bay.jpg)

## Install

Requires [Extended Propellants](https://github.com/Maximilian-Nesslauer/KSA-ExtendedPropellants). The engines use its propane and combustion data. No mod loader is needed.

- Borea: install Prisma from the content list. Borea adds Extended Propellants.
- By hand: copy `PurrlinePrisma` and `ExtendedPropellants` from the release zips into `Documents/My Games/Kitten Space Agency/mods/` and enable both.

You can install [Fairings by Purrline Rocketworks](https://github.com/Maximilian-Nesslauer/KSA-PurrlineFairings) together with Prisma. Use Prisma 1.2.0 with Fairings 1.0.1 to get the updated attachment rules in either load order. Both releases contain the same 2 m fairing, and the game loads it once. The fairing keeps its part IDs and connector order. If you still use Prisma 1.0.0, update Prisma before you enable Fairings.

To remove the mod, delete its folder. Vehicles with its parts do not load without it.

Works well with [Andoya Spaceport](https://github.com/Maximilian-Nesslauer/KSA-AndoyaSpaceport) (a pad for Prisma), [Facet](https://github.com/Maximilian-Nesslauer/KSA-PurrlineFacet) (satellites for the fairing) and [Fairings](https://github.com/Maximilian-Nesslauer/KSA-PurrlineFairings) (more fairings).

## Licence

Code and game data: MIT ([LICENSE](LICENSE)). Meshes, textures, logo and pictures: CC BY 4.0 ([LICENSE-ART](LICENSE-ART)). Credits: [NOTICE.md](NOTICE.md).

## Links

[Forum thread](https://forums.ahwoo.com/forums/kitten-space-agency/mod-releases/prisma-by-purrline-rocketworks.1633/) | [Issues](https://github.com/Maximilian-Nesslauer/KSA-PurrlinePrisma/issues)
