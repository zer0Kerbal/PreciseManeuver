---
permalink: /ManualInstallation.html
title: Manual Installation (no warranty coverage provided)
---

<!-- ManualInstallation.md v1.1.0.0
PreciseManeuver! (KPM)
created: 01 Oct 2019
updated: 02 Mar 2022 -->

<!-- based upon work by Lisias -->

# PreciseManeuver! (KPM)

***Provides simple craft building capability in flight mode to stock parts for Kerbal Space Program.***

PreciseManeuver! (KPM) is under zer0Kerbal's management!

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/ExtraplanetaryLaunchpads` AND `<KSP_ROOT>/GameData/PreciseManeuver`
* Extract the package's `PreciseManeuver/` folder into your KSP's as follows:
  * `<PACKAGE>/PreciseManeuver` --> `<KSP_ROOT>/GameData/PreciseManeuver`
    * Overwrite any preexisting file.
* Extract the package's `ExtraplanetaryLaunchpads/` folder into your KSP's as follows:
  * `<PACKAGE>/ExtraplanetaryLaunchpads` --> `<KSP_ROOT>/GameData/ExtraplanetaryLaunchpads`
    * Overwrite any preexisting file.

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/ExtraplanetaryLaunchpads` AND `<KSP_ROOT>/GameData/PreciseManeuver`
* Extract the package's `GameData/ExtraplanetaryLaunchpads` folder into your KSP's as follows:
  * `<PACKAGE>/GameData/ExtraplanetaryLaunchpads` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.
* Extract the package's `GameData/PreciseManeuver` folder into your KSP's as follows:
  * `<PACKAGE>/GameData/PreciseManeuver` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.

## The following file layout must be present after installation

```
<KSP_ROOT>
  [GameData]
    [ExtraplanetaryLaunchpads]
      [Localization]
        ...
      [Texture]
        ...
      [UI]
        ...
      License.txt
      License-KS.txt
    [PreciseManeuver]
      [Agencies]
        ...
      [Compatibility]
        ...
      [Contracts]
        ...
      [Flags]
        ...
      [Localization]
        ...
      [Parts]
        ...
      [Plugins]
        ...
      #.#.#.#.htm
      changelog.md
      Expat-MIT.txt
      readme.htm
      PreciseManeuver.version
    ...
  KSP.log
  ...
```

```mermaid
  graph LR
  %% file structure of PreciseManeuver! (KPM)
    id[("PreciseManeuver! File Structure")];
    style id1 fill:#f9f,stroke:#333,stroke-width:3px
    style id2 fill:#ff0,stroke:#333,stroke-width:2px
    style id3 fill:#bada55,stroke:#333,stroke-width:1px
      subgraph id1[Kerbal Space Program Root]
        KSP --folder--> gamedata
        KSP -. file .-> log>KSP.log]
      end
      subgraph id2 [GameData Folder]
        gamedata -- folder --> ExtraplanetaryLaunchpads
        gamedata -. file .-> ModuleManager[/ModuleManager.dll\]
        gamedata -- folder --> PreciseManeuver
      end
      subgraph id3 [PreciseManeuver and Extraplanetary Launchpads Folders]
        ExtraplanetaryLaunchpads -- folder --> elLoc(Localization) & Texture & UI
        PreciseManeuver -- folder --> Agencies & Compatability & Localization & Parts & Plugins %%& Textures
        PreciseManeuver -. file .-> a>#.#.#.#.htm] & b>Attribution.md] & c>changelog.md] & d>Expat-MIT.txt] & e>ManualInstallation.md & f>readme.htm] & g>PreciseManeuver.version]
        ExtraplanetaryLaunchpads -. file .-> aa>License.txt] & bb>License-KS.txt]
      Agencies --> 1[...]
      Compatability --> 2[...]
      Contracts --> 3[...]
      Flags --> 4[...]
      Localization --> 5[...]
      Parts --> 6[...]
      Plugins .-> 7[/Launchpad.dll\] & 41>EL.version] & 42>License.txt] & 43>License-KS.txt]
      %%Textures .-> 8[...]
      elLoc .-> 10[...]
      Texture .-> 20[...]
      UI .-> 30[...]
      end
```

### Dependencies

* [Module Manager][thread:mm]

[thread:mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-* "Module Manager"
