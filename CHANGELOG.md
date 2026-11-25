# Changelog

## 1.3.1

- Mark the mod as compatible with KSA 2026.11.25.5949. No functional changes.

## 1.3.0

Each of the nine Altair engines in the Altair Engine Bay now has its own engine controller, validated against KSA build version 2026.11.16.5901. All nine still light together in the first stage, and the Active switch in the part window of the engine bay still switches all nine together. A tool that controls engines, such as a flight computer, can now switch each engine on and off on its own, for example to land a returning first stage on the center engine or on three engines only. Part Ids, shapes, colliders, masses, fuel feeds, gimbals and the 2 m fairing are the same as in 1.2.0. Craft files and vehicles that have not launched yet are not affected. A Prisma that is in flight in a save from 1.2.0 or older loses the state of its engine bay when you load the save: the nine engines load switched off. Switch them on again with the Active switch in the part window of the engine bay.

## 1.2.0

- Give Stage 2 switchable 15 W avionics and a status light on its 400 kJ battery. Set radiation tolerance to 100 Gy, upset dose to 90 mSv and shielding to 1 g/cm2.
- Set Altair and the engine bay gimbals to 10 degrees per second and Altair Vac to 4 degrees per second.
- Add a faint stock plume trail for Altair and the engines in the Altair Engine Bay. It appears in atmosphere when **Plume trails** is enabled.
- Block new surface attachments on the jettisonable fairing halves and keep the shared 2 m fairing files identical to Fairings 1.0.1. Preserve existing part IDs and connector order.

## 1.1.2

Works with KSA build version 2026.11.16.5901 and needs it. KSA 2026.11.16.5901 moved the minimum throttle and the minimum pulse time of an engine from the combustion chamber to the rocket, so with Prisma 1.1.1 the Altair, the Altair Vac, the engine bay and the upper stage did not load. These values are now in the new place and are the same as before. The game also corrected the density of MMH, so each of the four RCS tanks of the upper stage now holds about 37 kg instead of 27 kg. Part Ids, shapes, colliders, masses and saved vehicles are the same as in 1.1.1. This version does not load on older KSA builds; use 1.1.1 there.

## 1.1.1

Fixes flickering faces on the raceway, validated against KSA build version 2026.11.10.5801. The end faces of the raceway covers on the Prisma Stage 1 Tank and on the Prisma Interstage had no texture area, so the game could not shade them, and they showed changing noise. These faces now have their own small texture area with the plain light grey paint of the cover. Only the mesh and the textures of these faces changed: part Ids, shapes, colliders, masses, the 2 m fairing and saved vehicles are the same as in 1.1.0.

## 1.1.0

New fairing, validated against KSA build version 2026.11.10.5801. The fairing half and base now come from the fairing family of Fairings by Purrline Rocketworks: the same shape and size, the same part Ids and connectors, new names (Fairing Half 2 m Medium, Fairing Base 2 m), a black carbon variant of the half (V key in the editor), a quilted acoustic blanket inside, six hull colliders instead of five, and a stronger split (930 N s instead of 800 N s). Vehicles that you saved with Prisma 1.0.0 load with their fairing. Prisma does not need Fairings by Purrline Rocketworks: it contains the same 2 m fairing. You can enable both mods together, in any order, and the game loads the fairing one time. All other parts are the same as in 1.0.0.

## 1.0.0

First release, validated against KSA build version 2026.11.10.5801: stage 1 tank and interstage, engine bay with nine Altair, Altair and Altair Vac, upper stage with RCS, fairing, payload mass simulator, hold-down ring and strongback. Requires Extended Propellants.
