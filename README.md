# TF2 Set class Regen health

- This plugin allows to change ones health regen per second.

## How to install.
- Download this repository (right top green button), and copy `setclasshealthregen.smx` on your plugins folder.

## CVars:

cvar name, default value, description.

-    "sm_rhenabled", "1", "Sets whether the plugin is enabled."

-    "sm_rhmode", "0", "Sets plugins mode, 0: sm_rhincrement = additive value to the default regen health for each class for everyone, 1: Custom health value for each class from each ones cvar"
-    "sm_rhteam", "1", "0: apply to all teams, 1: Only RED, 2: Only Blue"

-    "sm_rhincrement", "4", "Additive health added to everyone per second if sm_spmode = 1."

-    "sm_rhsoldier", "2", "Sets Soldiers regen health per second"
-    "sm_rhpyro", "2", "Sets Pyros regen health per second"
-    "sm_rhspy", "2", "Sets Spys regen health per second"
-    "sm_rhdemoman", "2", "Sets Demomans regen health per second"
-    "sm_rhsniper", "2", "Sets Snipers regen health per second"
-    "sm_rhengineer", "2", "Sets Engineers regen health per second"
-    "sm_rhheavy", "2", "Sets Heavys regen health per second"
-    "sm_rhscout", "2", "Sets Scouts regen health per second"
-    "sm_rhmedic", "2", "Sets Medics regen health per second"


## Config file:
- Config file located at `cfg/sourcemod/setclasshealthregen.cfg`.

## Current known bugs:
none

## This plugin is not fully tested, if you find any issues, report it to [ISSUES](https://github.com/Frenzoid/TF2_SetClassHealthRegen/issues) or [send me a private message via Steam](https://steamcommunity.com/id/MrFren/).
