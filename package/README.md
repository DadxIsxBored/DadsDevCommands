# DadsDevCommands

DadsDevCommands provides server administration and expanded developer-command tools for Valheim 1.0.12.

## Features

- Enables the console without a launch argument.
- Enables developer commands for authorized administrators.
- Supports server-side command execution and permissions.
- Adds command aliases, multi-command lines, substitution, improved completion, and modifier-aware binds.
- Adds map, teleport, inventory, repair, event, player, world, and server utilities.
- Includes configurable automatic devcommands, debug mode, fly, ghost, god, and no-cost modes.
- Supports client-only use; server installation enables full server administration and permissions.

## Installation

Install BepInExPack for Valheim, then place `DadsDevCommands.dll` in `BepInEx/plugins/DadsDevCommands/`. Install the same package on the server for server-side execution and permission control.

Do not run DadsDevCommands and Server Devcommands at the same time because they patch and register the same game commands.

Configuration path: `BepInEx/config/com.dadisbored.dadsdevcommands.cfg`.

## Prior work

DadsDevCommands is adapted from Jere Kuusela's public-domain Server Devcommands project. The upstream license and detailed attribution are included in the package.

