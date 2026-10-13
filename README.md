# timeless-sim

Gear checker for World of Warcraft: it simulates your character with
[SimulationCraft](https://www.simulationcraft.org/) right on your PC and
shows, on a local dashboard, which items in your bags (and Great Vault) are
upgrades -- today, and once fully upgraded.

This repository only holds the downloads.

## Install

1. Install the [SimulationCraft addon](https://www.curseforge.com/wow/addons/simulationcraft).
2. Download the zip from the [latest release](../../releases/latest) and
   unzip it anywhere (not inside Program Files).
3. Double-click `timeless-sim.exe`. Windows may warn "Windows protected
   your PC" the first time: click "More info" -> "Run anyway".

A dashboard opens in your browser and lists anything left to set up. If
WoW was running, exit it and start it again once so the companion addon
loads. Keep the black console window open while you play.

## Use

1. In WoW, open your character sheet (`C`) and click **Sim & Reload**
   under it (or type `/tsim`).
2. Your UI reloads and the character shows up on the dashboard. The first
   simulation takes a few minutes; later ones only redo what changed.
3. Do it again whenever you change gear, talents or spec.

When your first results appear, a short tour shows you around the
dashboard; the **?** button next to settings replays it.

Right after login the button may read *Loading items...* -- click anyway,
and when it changes to *Ready - click to reload*, click once more.

**Great Vault:** open the vault in-game and click the same **Sim & Reload**
button under it, then the chest icon next to your character on the
dashboard.

**Healers:** SimulationCraft simulates damage, not healing, so healer specs
show as a greyed-out tab. For Restoration Druid and Shaman, Settings has a
**beta** option to rank their gear by damage instead.

## Updates

When a new version is out, the dashboard shows a banner -- click
**Update & restart** and it updates itself, keeping all your data.
