# Additional Icons for FoundryVTT

![Latest Release Download Count](https://img.shields.io/github/downloads/p4535992/foundryvtt-additional-icons/latest/module.zip?color=2b82fc&label=DOWNLOADS&style=for-the-badge)

[![Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Fadditional-icons&colorB=006400&style=for-the-badge)](https://forge-vtt.com/bazaar#package=additional-icons)

![Foundry Core Compatible Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fraw.githubusercontent.com%2Fp4535992%2Ffoundryvtt-additional-icons%2Fmaster%2Fmodule.json&label=Foundry%20Version&query=$.compatibleCoreVersion&colorB=orange&style=for-the-badge)

![Latest Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fraw.githubusercontent.com%2Fp4535992%2Ffoundryvtt-additional-icons%2Fmaster%2Fmodule.json&label=Latest%20Release&prefix=v&query=$.version&colorB=red&style=for-the-badge)

[![Foundry Hub Endorsements](https://img.shields.io/endpoint?logoColor=white&url=https%3A%2F%2Fwww.foundryvtt-hub.com%2Fwp-json%2Fhubapi%2Fv1%2Fpackage%2Fadditional-icons%2Fshield%2Fendorsements&style=for-the-badge)](https://www.foundryvtt-hub.com/package/additional-icons/)

![GitHub all releases](https://img.shields.io/github/downloads/p4535992/foundryvtt-additional-icons/total?style=for-the-badge)

[![Translation status](https://weblate.foundryvtt-hub.com/widgets/additional-icons/-/287x66-black.png)](https://weblate.foundryvtt-hub.com/engage/additional-icons/)

### If you want to buy me a coffee [![alt-text](https://img.shields.io/badge/-Patreon-%23ff424d?style=for-the-badge)](https://www.patreon.com/p4535992)

Some additional icons

## Installation

It's always easiest to install modules from the in game add-on browser.

To install this module manually:
1.  Inside the Foundry "Configuration and Setup" screen, click "Add-on Modules"
2.  Click "Install Module"
3.  In the "Manifest URL" field, paste the following url:
`https://raw.githubusercontent.com/p4535992/foundryvtt-additional-icons/master/module.json`
4.  Click 'Install' and wait for installation to complete
5.  Don't forget to enable the module in game using the "Manage Module" button

## Other modules

[Additional Cards](https://github.com/p4535992/foundryvtt-additional-cards) is a module that adds three new Foundry V9 card decks for import from a compendium
[Additional Token Frames](https://github.com/p4535992/foundryvtt-additional-token-frames) is a module that add token frames

# Build

## Install all packages

```bash
npm install
```

### dev

`dev` will let you develop you own code with hot reloading on the browser

```bash
npm run dev
```

### build

`build` will build and set up a symlink between `dist` and your `dataPath`.

```bash
npm run build
```

### build:watch

`build:watch` will build and watch for changes, rebuilding automatically.

```bash
npm run build:watch
```

### prettier-format

`prettier-format` launch the prettier plugin based on the configuration [here](./.prettierrc)

```bash
npm run-script prettier-format
```

### lint

`lint` launch the eslint process based on the configuration [here](./.eslintrc.json)

```bash
npm run-script lint
```

### lint:fix

`lint:fix` launch the eslint process with the fix argument

```bash
npm run-script lint:fix
```

### build:json

`build:json` unpack LevelDB pack on `src/packs` to the json db sources in `src/packs/_source`very useful for backup your items and manually fix some hard issue with some text editor

```bash
npm run-script build:json
```

### build:clean

`build:clean` clean packs json sources in `src/packs/_source`. NOTE: usually this command is launched after the command `build:json` and after make some modifications on the json source files with some text editor, but before the `build:db`

```bash
npm run-script build:clean
```

### build:db

`build:db` packs the json db sources in `src/packs/_source` to LevelDB pack on `src/packs` with the new jsons. NOTE: usually this command is launched after the command `build:json` and after make some modifications on the json source files with some text editor

```bash
npm run-script build:db
```

## [Changelog](./CHANGELOG.md)

## Issues

Any issues, bugs, or feature requests are always welcome to be reported directly to the [Issue Tracker](https://github.com/p4535992/foundryvtt-additional-cards/issues ), or using the [Bug Reporter Module](https://foundryvtt.com/packages/bug-reporter/).

## License

These icons are packaged with and provided for use in this module and may not be redistributed or used outside of this module except as permitted by a separate license agreement between the original copyright holder of these icons. These license terms apply to all icons within this directory.

Assets in this bundle include an Extended License that allows you to develop your own digital or physical card games. For more details, please refer to the full terms.

### 

https://marketplace-website-node-launcher-prod.ol.epicgames.com/ue/marketplace/en-US/profile/KatGrabowska?count=20&sortBy=effectiveDate&sortDir=DESC&start=0


### OpenGameArt.Org Painterly Spell Icons

J. W. Bjerk (eleazzaar) -- www.jwbjerk.com/art -- find this and other open art at: http://opengameart.org

https://opengameart.org/content/painterly-spell-icons-part-1
https://opengameart.org/content/painterly-spell-icons-part-2
https://opengameart.org/content/painterly-spell-icons-part-3
https://opengameart.org/content/painterly-spell-icons-part-4

### Humble 7000 Game Dev ICONS Bundle EULA

This module includes icon artwork licensed from [Humble Bundle](https://support.humblebundle.com/hc/en-us/articles/360046217533)

https://support.humblebundle.com/hc/en-us/articles/360046217533

"End Product" means any digital product, games, websites, software, applications, video content, audio content.

1. Seller grants to the Purchaser a non-exclusive perpetual license to:
- use and/or modify or manipulate the Licensed Assets and make a Derivative Work from it;
- use Licensed Assets to create an unlimited number of End Products for Sale, in which the End Product for Sale may be sold an unlimited number of times;
- use the Licensed Assets in End Product that are either used for the Purchaser's own personal use or used for the Purchaser's commercial use in which case it may be distributed, sold and supplied by the Purchaser for any fee;

2. A License does not allow the Purchaser to:
- Use, sell, share, transfer, give away, sublicense or redistribute the Licensed Asset or Derivative Works other than as part of the relevant End Product;
- Extract the Licensed Asset or Derivative Works and use them outside of the relevant End Product.
- Use or/and incorporated the Licensed Asset or Derivative Works into a logo, service mark or trademark.
- Purchaser may not use the Licensed Asset or Derivative Works in End Product containing models and/or property in a manner that is unlawful, harmful, abusive, racially or ethnically offensive, defamatory, deceptive, infringing, invasive of personal privacy or publicity rights, harassing, humiliating to other people, libelous, obscene, threatening, profane, or promotes racism, bigotry, hatred or physical harm of any kind against any group or individual, or is otherwise objectionable.

### SVG Icons from Game-Icons.net

The dnd5e system for Foundry Virtual Tabletop includes icon artwork licensed from Game-icons.net under the Creative Commons license. These icons are packaged with and provided for use in the dnd5e system under their respective licenses, as noted below.

/svg/hit-points.svg - "Heart plus" by Zeromancer under CC0 PDD
/svg/item-grant.svg - "White book" by Willdabeast under CC BY 3.0
/svg/scale-value.svg - "Dice target" by Delapouite under CC BY 3.0

### CODE

This package is under an [MIT license](LICENSE) and the [Foundry Virtual Tabletop Limited License Agreement for module development](https://foundryvtt.com/article/license/).

## Credit

Thanks to anyone who helps me with this code! I appreciate the user community's feedback on this project!
