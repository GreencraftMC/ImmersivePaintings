# Immersive Paintings

[![Crowdin](https://badges.crowdin.net/immersive-collection/localized.svg)](https://crowdin.com/project/immersive-collection)

CurseForge: https://www.curseforge.com/minecraft/mc-mods/immersive-paintings

Modrinth: https://modrinth.com/mod/immersive-paintings

Config docu here: https://github.com/Luke100000/ImmersivePaintings/wiki/Config

Modpack/Datapack Creator help: https://github.com/Luke100000/ImmersivePaintings/wiki/Custom-Paintings

## GreencraftMC Fork - Security Features

This fork adds security hardening on the `1.21.1` and `26.2` branches:

- **URL whitelist** — Image downloads are restricted to a configurable list of allowed hosts (`i.imgur.com`, `cdn.discordapp.com`, etc.) with size limit and download timeout.
- **Painting protection** — Only the creator of a painting can modify or delete it. Permission checks are enforced on the server side.
