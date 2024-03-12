# Sunroof

Sunroof is a [Vesktop](https://github.com/Vencord/Vesktop) fork

## Installing

Find the required installer you need [here](https://github.com/verticalsync/Sunroof/releases/tag/latest).

## Windows contribution

You will get test errors about venmic, you can ignore these as it's a linux only module.

## Building from Source

Packaging will create builds in the dist/ folder

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
