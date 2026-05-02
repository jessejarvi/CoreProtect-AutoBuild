# CoreProtect-AutoBuild

[![Build and Deploy](https://github.com/Midnight-2004/CoreProtect-AutoBuild/actions/workflows/build.yml/badge.svg)](https://github.com/Midnight-2004/CoreProtect-AutoBuild/actions/workflows/build.yml)

Automatically pulls and builds CoreProtect once every Sunday. Forked from the original author just to translate this to finnish.

## Why does this repository exist?

Since the release of version `22.4` in May 2024, CoreProtect has not published an update for Minecraft 1.21. However, users can obtain the latest builds by supporting the project on Patreon.

Although the developer has not updated the plugin on SpigotMC or Modrinth, the CoreProtect GitHub repository is still being updated continuously. Because of this, we are able to maintain a repository that synchronizes and builds the latest version.

## Notes

The CoreProtect build produced by this repository is a `development` version. According to feedback from other users on SpigotMC and Discord, **these manually built versions pulled from the repository** cannot use databases from version `22.4` or earlier, so you need to delete the old database before continuing to use these plugin versions.

Tips:

- If you use an `SQLite` database, I recommend adding a `.disabled` suffix to the old database and plugin to disable them. If you need to restore them, just remove the suffix.
- If you use `MySQL`, why not just create a new database?


## CoreProtect introduction

![CoreProtect](https://userfolio.com/uploads/coreprotect-banner-v19.png)

[CoreProtect](https://github.com/PlayPro/CoreProtect) is a blazing-fast data logging and anti-griefing tool for Minecraft servers.

For detailed plugin documentation, visit [coreprotect.net](https://coreprotect.net).

### bStats

[![bStats Graph Data](https://bstats.org/signatures/bukkit/CoreProtect.svg)](https://bstats.org/plugin/bukkit/CoreProtect)

## Star History of this repository

[![Star History Chart](https://api.star-history.com/svg?repos=Midnight-2004/CoreProtect-AutoBuild&type=Date)](https://www.star-history.com/#Midnight-2004/CoreProtect-AutoBuild&Date)
