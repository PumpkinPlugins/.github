# PumpkinPlugins
The first organization dedicated to developing high quality plugins for the [Pumpkin](https://github.com?pumpkin-MC/Pumpkin) minecraft server software.

![Discord](https://img.shields.io/discord/1380863905932251228?link=https%3A%2F%2Fdiscord.gg%2FJMwGrM6c)

## Plugin list
### PLua
The latest addition to the PumpkinPlugins organization. This plugin acts as a PoC (Proof-of-Concept) plugin to demonstrate the feasibility of writing external runtimes for [Pumpkin](https://github.com?pumpkin-MC/Pumpkin).

This plugin allow server admins to quickly and easily write plugins using the Lua programming language.

While still being in a very early stage of development, it already allows listening for events, broadcasting messages to players, and logging to the server console, with more features coming in the near future.

Working features:
- Listening for basic events (player join/leave, block place/destroy, chat messages)
- Logging to the console
- Broadcasting a server-wide message

Planned features:
- Command registration
- Player management (allowing to interact with the internal Player object)

### PumpkinVerse
> This plugin is currently not fully operational, but fixes are being worked on

This plugin aims to provide similar functionality to that of the very well known Multiverse-Core plugin for Bukkit-based minecraft server.

Working features:
- World creation
- World deletion
- Listing worlds and their details

Broken features:
- Teleporting to a different world (this is due to a bug in [Pumpkin](https://github.com?pumpkin-MC/Pumpkin), which is being worked on)

Planned features:
- Custom generators

### CommandLimiter
A very basic permission plugin allowing to whitelist or blacklist specific users from running specific commands.
