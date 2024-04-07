![logo](./static/icon.png)

# Sunroof

[![Sunroof](https://img.shields.io/badge/Suncord-orange?style=flat)](https://github.com/verticalsync/Suncord)
[![Tests](https://github.com/verticalsync/Sunroof/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/verticalsync/Sunroof/actions/workflows/test.yml)
[![Discord](https://img.shields.io/discord/1207691698386501634.svg?color=768AD4&label=Discord&logo=discord&logoColor=white)](https://discord.gg/VasF3Ma4Ab)

Sunroof is a fork of [Vesktop](https://github.com/Vencord/Vesktop).

## Main features
- Much more lightweight and faster than the official Discord app
- Linux Screenshare with sound & wayland

**Extra included changes**
- Suncord preinstalled
- Custom Splash animations from [this PR](https://github.com/Vencord/Vesktop/pull/355)

**Not yet supported**:
- Global Keybinds
  

You can join our [discord server](https://discord.gg/VasF3Ma4Ab) for commits, changes, chat or even support.

## Installing

Find the required installer you need [here](https://github.com/verticalsync/Sunroof/releases/latest).
  
## Building from Source
Packaging will create builds in the dist/ folder
> [!NOTE]
> On Windows, You will get test errors about venmic, you can ignore these as it's a linux only module.

```sh
git clone https://github.com/verticalsync/Sunroof
cd Sunroof

# Install Dependencies
pnpm i

# Either run it without packaging
pnpm start

# Or package
pnpm package
# Or only build the pacman target
pnpm package --linux pacman
# Or package to a directory only
pnpm package:dir
```
