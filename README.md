# KSPatches

A patch pack for Kerbal Space Program, focused on increasing Isp and TWR on rockets.

* [Features](#features)
* [Dependencies](#dependencies)
* [Installation](#installation)
* [External Compatibility](#installation)
* [Contributing](#contributing)
* [Licensing](#licensing)

## Features

This mod features several improvements to the Isp of a lot of engines, mostly converting them to hydrolox Isp levels.

* **Hydrogen Isp** The aerospike, SSME, Rhino, Mammoth, Skipper, Skiff, Poodle, and Mainsail all get hydrogen Isps, in a range of 430-460s.
* **Methane Isp** The Terrier engine is the only one with this Isp value, one of 358s.
* **Fluorine Isp** The Wolfhound and Cheetah engines are based on better mixtures than hydrogen.
  * The Wolfhound is based on lithium-fluorine-hydrogen tripropellant, with an Isp of 566s to match.
  	* My headcanon is that this engine has RTGs to accelerate the (incredibly toxic) exhaust by another ~230m/s.
  	* This is as far as I've learned; I am **not** learning how to edit effects and to use ModuleWaterfallFX.
  * The Cheetah is based on fluorine-hydrogen, with some magic that makes its plume blue and not faint pink.
  * The Poodle engine was the measuring stick. If anything was better than it, it got an Isp above 470s. Nervs are exempt.
 * **Realistic Isp** Edits Isp for Rutherford and Merlin vacuum engines, to around the 345s range.

This mod also features fuel tank and engine weight reduction.

* All fuel tanks have their dry weight reduced to 1/3 normal.
* **WORK IN PROGRESS** All fuel tanks and engines from Far Future Technologies are effectively weightless.
  * This is meant to make city-sized interstellar vehicles feasible, with mass ratios of 10000:1 or higher.
* Engines have their weight reduced by anywhere from 1/2 normal to 1/4 normal.

## Dependencies

### Required
These components are required for the mod to function.
* [ModuleManager (4.2.3)](https://github.com/sarbian/ModuleManager)
### Recommended
These mods are very highly recommended:
* [ReStock](github.com/porktoberrevolution/restocked)
* [Waterfall](github.com/post-kerbin-mining-corporation/Waterfall)
* [Restock Waterfall Expansion](https://spacedock.info/mod/3149/Restock%20Waterfall%20Expansion)

## Installation

To install, place the KSPatches folder inside your Kerbal Space Program GameData folder. If asked to overwrite files, please do so.

## External Mod Compatibility

This mod includes compatibility patches for the following mods:
* Making History Expansion: Provides Skiff, Wolfhound, Cheetah engines, and 1.875m + 5m fuel tanks.
* NF Launch Vehicles: Provides 7.5m and 5m fuel tanks.
* ReStockPlus: Patches all fuel tanks included there, including the Pug, which gets patched twice.
* Any mod you can think of that adds engines or tanks: because the MM patches apply to every engines and (LFO) tanks from **every mod**.

## Contributing

I certainly accept pull requests. Add mods on the wishlist to the engine and tank weight adjustments.

### Mod Wishlist

Mods on the wishlist include:
* Near Future Launch Vehicles by Nertea (done with tanks, patch engines)
* CryoEngines by Nertea (patch engines)
* CryoEngines Extensions by Kavaeric (make LFO patch)
* CryoTanks by Nertea (patch tanks)
* ReStockPlus by Nertea (patch Corgi, Caravel, Yorkie, Schnauzer engine Isp)
or any mod you can think of that adds engines or fuel tanks. The SpaceY suite comes to mind.

## Licensing

This patchset is hereby licensed under the WTFPLv2 license. It's only a paragraph long, and I'm sure you can get the gist of it.

```
DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                   Version 2, December 2004
 
Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>

Everyone is permitted to copy and distribute verbatim or modified
copies of this license document, and changing it is allowed as long
as the name is changed.
 
           DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
  TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

 0. You just DO WHAT THE FUCK YOU WANT TO.
```

