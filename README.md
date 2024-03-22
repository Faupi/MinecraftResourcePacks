# Setup:
## Prerequisites:
1. Download the repository with `Code -> Download ZIP` or [click this link](https://github.com/Faupi/MinecraftResourcePacks/archive/refs/heads/main.zip)
1. Open the archive in WinRAR or Windows Explorer
1. Copy the contents into the profile's directory `resourcepacks` folder
    - By default it's `%APPDATA%/.minecraft/resourcepacks`, you can run that with Win+R

## Automated:
By default, if you do not have a custom resource pack list already set up, the modpack should handle the default order.

**If you notice issues with textures or such, you can reload the default order by:**
1. Open Options
1. Go to Resource Packs
1. Hold T -> Resource packs should reset to default (modded)

## Manual:
### Order:
Some packs require to be in a specific order to work properly together.

Going by the ordering within the Minecraft resource pack menu (top to bottom priority):
- Better Leaves / FastFancy Bushy Leaves
- Reimagined FA Patch (Fresh Animations)
- Fresh Animations
- Reimagined Fixed
- Reimagined
- Eating Animations base
    - __Due to the custom Eating Animations handling, this is one required for them to show properly__ (built-in mod resources are bugged in the current version)

Every other pack is optional and can be anywhere in the order (but preferably above the ones listed above)

*NOTE: If the resource pack reload takes a long time, it's probably Visual Enchantments*
