# DadsDevCommands

DadsDevCommands is a Valheim 1.0.12/BepInEx 5.4.2350 server-administration and developer-command package.

It includes console enablement, authorized server commands, permissions, aliases, multiple commands per line, substitutions, improved autocomplete, enhanced binds, automatic developer modes, map utilities, player utilities, inventory utilities, teleportation, repair, event control, undo/redo, and server execution.

## Build

```powershell
.\build.ps1 -Package
```

The build requires the Valheim 1.0.12 managed assemblies and BepInEx 5.4.2350 core assemblies at the paths declared in `DadsDevCommands.csproj`.

## Installation

Place `DadsDevCommands.dll` in `BepInEx/plugins/DadsDevCommands/`. For full server-side commands and permission enforcement, install it on both the administrator client and server.

DadsDevCommands and Server Devcommands must not be loaded together.

## Attribution

This project is adapted from Jere Kuusela's Server Devcommands 1.113.0 source, which is released under the Unlicense. See `THIRD_PARTY.md` and `LICENSE`.

