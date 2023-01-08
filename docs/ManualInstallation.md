---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.1.8.1
Precise Maneuver (PM)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Precise Maneuver (PM)

[Home](./index.md)

Precise Maneuver (PM) plugin provides a window for more precise maneuver node editing in map view.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `Morse` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/Morse/PreciseManeuver`
* Extract the package's `Morse/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/Morse` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/Morse/PreciseManeuver`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/Morse/PreciseManeuver`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/Morse/PreciseManeuver`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [Morse]
      ...
      + [PreciseManeuver]
        + [Localization]
          ...
        + [Plugins]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * BSD-2-Clause.txt
        * changelog.md
        * ManualInstallation.htm
        * PreciseManeuver.version
        * readme.htm
      ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none