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

Provides simple craft building capability in flight mode to stock parts for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/PreciseManeuver`
* Extract the package's `PreciseManeuver/` folder into your KSP's as follows:
  * `<PACKAGE>/PreciseManeuver` --> `<KSP_ROOT>/GameData/PreciseManeuver`
    * Overwrite any preexisting file.

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/PreciseManeuver`
* Extract the package's `GameData/PreciseManeuver` folder into your KSP's as follows:
  * `<PACKAGE>/GameData/PreciseManeuver` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  [GameData]
    [PreciseManeuver]
      [Localization]
        ...
      [Plugins]
        PreciseManeuver.dll
        PreciseManeuver.Unity.dll
        precisemaneuverprefabs
        ...
      #.#.#.#.htm
      changelog.md
      BSD-2-Clause.txt
      readme.htm
      PreciseManeuver.version
    ...
  KSP.log
  ...
```

### Dependencies

* none
