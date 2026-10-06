# kihtli plugins

Custom Dalamud plugin repository.

## Installation

Add the following URL in `/xlsettings` → **Experimental** → **Custom Plugin Repositories**, enable it and save:

```text
https://raw.githubusercontent.com/kihtli/plugins/main/repo.json
```

Then open `/xlplugins` and search for the plugin name.

| Plugin | Description | Source |
| --- | --- | --- |
| Relic Atlas | Combat relic progression, remaining materials and per-type Atma farming requirements. | [kihtli/RelicAtlas](https://github.com/kihtli/RelicAtlas) |
| Outfit Studio (testing only) | Refit Penumbra outfits between compatible bodies and generate destination size options. Initial experimental prerelease. | [kihtli/OutfitStudio](https://github.com/kihtli/OutfitStudio) |

Relic Atlas requires Dalamud API 15. The optional Umbra extension is installed separately through Umbra; instructions are in the source repository.

Outfit Studio requires Dalamud API 15 and Penumbra. Enable Dalamud's plugin testing option to see and install it. It is offered only as a testing release; review converted outfits in game. See its [initial prerelease](https://github.com/kihtli/OutfitStudio/releases/tag/v0.1.9) for requirements and known limits.
