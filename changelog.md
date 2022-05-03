# Changelog  
  
| modName    | PreciseManeuver (KPM)                                             |
| ---------- | ----------------------------------------------------------------- |
| license    | BSD-2-Clause                                                      |
| author     | radistmorse and zer0Kerbal                                        |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/207261-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/PreciseManeuver)        |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/PreciseManeuver)      |
| spacedock  | (https://spacedock.info/mod/2998)                                 |
| ckan       | PreciseManeuver                                                   |

## 2.4.99.0-adoption `<Kerbal Floating Point Precision>` edition

## adopted by zer0Kerbal

* 25 Mar 2022
* Released for KSP 1.12.3

### Code

* Compile
  * .NET 4.7.2
  * C# 10.0
* Update
  * [PreciseManeuver.csproj]
  * [PreciseManeuver.Unity.csproj]
  * [PreciseManeuver.sln]

### Unity

* Recompile Assets
  * [precisemaneuverprefabs]
  * using Unity 2019.4.18f1 LTS

* create
  * GameData/PreciseManeuver/
    * Localization folder 📁
      * Localization/[readme.md] v2.1.0.1
      * Localization/[quickstart.md] v1.0.1.0
        * create: [en-us.cfg]
        * create [es-es.cfg]
        * create [de-de.cfg]
        * create [ja.cfg]
        * create [ru.cfg]
        * create [zn-cn.cfg]
    * delete old [localizations.cfg]

### Localization

* split localization into separate languages for easier handling
  * closes #12 - English <us-en.cfg>
  * closes #14 - German (Deutsch) <de.cfg>
  * closes #15 - Spanish (Español) <es-es.cfg>
  * closes #18 - Japanese(日本語) <ja.cfg>
  * closes #19 - Russian (Русский) <ru.cfg>
  * closes #20 - Simplified Chinese (简体中文) <zh-cn.cfg>
  * closes #29 - split localization into separate languages for easier handling
  * updates #11 - Localization - Master

### Create

* folder structure
  * docs/
    * Code/
    * LegalMumboJumbo/
      * [License.md]
      * [FORUM-01.png]
  * [404.md]
  * [Attribution.md]
  * [BasicInstructions.md]
  * [Localizations.md]
  * [ManualInstallation.md]
  * [readadme.md] v1.6.6.0
* root/
* _releasenotes
  * .gitattributes
  * .gitignore
  * .version file
  * changelog.md
  * [_buildJSON] v1.3.3.6.3
  * [_buildRelease] v1.1.3.1
  * [_deploy] v1.1.3.2
  * [_gitClean] v1.0.2.0
  * [_pullIssues] v1.1.0.1
  * [_pullReleaseNotes] v1.1.01
  * json/[_release] v1.0.3.0
* github/
  * [.imgbotconfig] v2.0.0.0
  * [_settings] v1.0.9.0
    * workflows/
      * [AVC-VersionFileValidator] v1.3.1
      * [createIndexesfromMarkdown] v1.0.1.0
      * [greetings] v1.1.0.1

## Status

* Issues
  * closes #9 * 2.4.99.0 Social Media
  * closes #8 * 2.4.99.0 Update Documentation
  * closes #7 * 2.4.99.0 Verify Legal Mumbo Jumbo
  * closes #6 * PreciseManeuver 2.4.99.0-adoption `<Kerbal Floating Point Precision>` edition

---

## Version 2.4.4.0 - for KSP 1.12.3 [13-Mar-2022]

* #2 - Screenshots - contributed by zer0Kerbal
* #4 - Repo work - contributed by zer0Kerbal
* #12 - English <us-en.cfg>
* #14 - German (Deutsch) <de.cfg>
* #15 - Spanish (Español) <es-es.cfg>
* #18 - Japanese(日本語) <ja.cfg>
* #19 - Russian (Русский) <ru.cfg>
* #20 - Simplified Chinese (简体中文) <zh-cn.cfg>
* #29 - split localization into separate languages for easier handling

---

## 2.4.4

* 2019-10-20
* KSP 1.8
* Update for newer unity engine

---

## 2.4.3

* 2019-10-12
* KSP 1.7
* Small correction to maneuver select logic
* Remove compatibility checker. It's more annoyance than help.

---

## 2.4.2

* 2019-03-23
* KSP 1.6
* German translation
* Fixed menu button in scenarios
* Better parameters for KAC

---

## 2.4.1

* 2018-03-07
* Recompile for KSP 1.4

---

## 2.3.2

* 2018-01-01
* Small fixes
* Use a library function for time display

---

## 2.3.1

* 2017-06-12
* Spanish localization
* Fix the incorrect scale behaviour
* Absolute values in orbit info fixed
* +/- orbit buttons are now repeatable

---

## 2.3.0

* 2017-06-04
* KSP 1.3.0
* Localization support
* Tooltips added
* All text is replaced with TMPros
* And all inputs are also replaced with TMPros
* And even the text in dropdowns was replaced with TMPros
* Seriously, I can't beleive how many hidden places there are with the fucking text components
* Did I mention I replaced the text with TMPros? Because I did

---

## 2.2.5

* 2017-02-19
* Fix dropdown blocker which caused the UI block in some cases

---

## 2.2.4

* 2017-02-03
* Reworked AN/DN calculation

---

## 2.2.3

* 2017-01-30
* Menuever copy format now is the same as in TWP
* Several minor bugfixes

---

## 2.2.2

* 2016-12-27
* Calculate the correct ej. angle when pasting from TWP

---

## 2.2.1

* 2016-12-22
* KSP 1.2.2
* Orbit tools redesigned (icons instead of text)
* copy/paste for maneuvers (compatible with TWP)

---

## 2.2-pre

* 2016-09-29
* Works with KSP 1.2
* New +/- orbit buttons
* New AP/PE buttons for gizmo
* Axis input fields are now editable
* Clickthrough prevention

---

## 2.1

* 2016-07-14
* Removed the dead zone in gizmo tool
* Adjusted the sensitivity of the gizmo
* Exapanded "undo" to save more than one change
* Changes from gui buttons and hotkeys now also undoable
* Fixed KAC integration
* Fixed the weird toolbar behaviour in some cases
* Eye candy for main window
* Added the ability to put the main window into background
* Honor the F2 (hide the UI) hotkey

---

## 2.0

* 2016-05-06
* Deprecating IMGUI, new prefab-based GUI
* Scalable GUI
* Modular structure for GUI
* New preset module for saving and loading maneuvers
* New gizmo module that resembles the stock gizmo

---

## 1.1.1

* 2016-01-05
* Check orbit parameters for sanity before use
* Change GUID to unique one
* Small GUI fixes

---

## 1.1

* 2015-12-27
* New tools: circularize and orbit up/down
* Lots of new hotkeys
* Ability to unset hotkeys
* Little tweaks to make GUI more responsive

---

## 1.0.0

* 2015-12-13
* Let's start a brand new changelog here, so now this is an initial release
* The histrory of the PreciseNode plugin can be found here:
  https://github.com/blizzy78/ksp-precisenode/blob/master/PreciseNode/CHANGES.txt

---

## 1.2.4, 2016-10-15

* Updated for KSP 1.2.0.
* Please note that the 32-bit version of KSP will no longer be supported.

---

## 1.2.3, 2016-05-02

* Updated for KSP 1.1.2.
* Now uses KSP-AVC for version checking. If KSP-AVC is not installed, the bundled
  MiniAVC will be used.

---

## 1.2.2, 2016-04-21

* Updated for KSP 1.1.0.

---

## 1.2.1, 2015-11-14

* Fixed a bug with loading/saving the intuitive maneuver node handles option.
* Fixed a bug that occurred when patched conics were not yet available in career mode.

---

## 1.2.0, 2015-11-10

* Updated for KSP 1.0.5.
* Added intuitive behavior for maneuver node handles (code by TechnocratiK.) This can be enabled
  in the options window. The intuitive behavior is most useful for normal/anti-normal burns
  (ie. inclination changes.)
* Orbit information now also shows the inclination.
* Fixed a bug in the Kerbin/Earth time conversion.
* Disabled KSP compatibility check for the time being.

---

## 1.1.3, 2015-05-02

* Fixed NullReferenceException in map mode.
* Updated for KSP 1.0.2.

---

## 1.1.2, 2014-12-16

* Updated for KSP 0.90.0.

---

## 1.1.1, 2014-10-09

* Fixed a bug in the KSP compatibility check.

---

## 1.1.0, 2014-08-02

* The +/- buttons have been combined into one button. Left-clicking now acts as plus, whereas
  right-clicking acts as minus.
* Fixed some bugs in the calculations of ejection angle and ejection inclination.
* If activated in the options, the conics window is now always displayed regardless of the
  visibility of the main window.

---

## 1.0.0, 2014-07-27

* In addition to the automatic update check, the plugin now also gets KSP versions
  from the update check server. In case the currently running KSP version is one of
  those versions, the plugin will not complain about being incompatible with this
  KSP version. This saves both players' and the plugin author's time.
* Updated for KSP 0.24.2.

---

## 0.14, 2014-07-25

* Updated for KSP 0.24.1.

---

## 0.13, 2014-07-18

* Updated for KSP 0.24.0.
* The RP-9f Craft Locator part is now gone.

---

## 0.12, 2014-06-10

* Added new buttons "MS" and "MR" to memorize and recall the current maneuver node's settings,
  respectively.
* DN/AN buttons should no longer flicker if the relative/equatorial inclination is almost zero.

---

## 0.11, 2014-04-09

* The button "Focus Vessel" should now work as intended.
* Time and duration displays should now honor the Earth time/Kerbin time setting.
* Added a button to delete the current maneuver node.

---

## 0.10, 2014-04-02

* Added a new option to show/hide conics controls in the main window.
* In addition to the ejection angle, the ejection inclination will be displayed.
* The RP-9f Craft Locator (the part that saves maneuver nodes into the save file) has been removed.
  KSP itself can save maneuver nodes now.
  Note: For the time being, your existing craft should be fine. You simply cannot select the part
  in the editor any longer. Be advised to replace existing craft using this part because it will
  be removed permanently at some future point. You should be able to remove it from craft files in
  the editor.
* The buttons to modify a maneuver node's time will be disabled now if they are not applicable with
  respect to the node's current time.

---

## PreciseNode 0.9

* Added a PartModule to save and load Maneuver Nodes: ModuleNodeSaver.
  * No additional parameters are needed, there are no right-click options.
* Talisar provided a part for ModuleNodeSaver.
  * The RP-9f Craft Locator is available under the Control parts section.
  * In career mode it is under Advanced Flight Control for 8000 unlock, 1200 price.
* a.g. provided code to fix an issue with Unity on Linux where hotkeys were being
    activated even while a text field had focus.
* Added Majiir's compatibility checker for KSP version checking.
  * This will not disable any functions, it is purely used for warning the user.
* Added the ability to merge a node with a previous node on the Trip Info screen.
* Replaced the +/-10K time buttons with AN/DN snap buttons.
  * If you have a target the buttons will snap to AN/DN of the target, otherwise
    they will snap to the equatorial AN/DN.

---

## PreciseNode 0.8.1

* Fixed node update during burn issue (editing a node without using the gizmo first).
* Changed the options and keymapper buttons to toggle-like functionality.

PreciseNode 0.8
* Fixed null reference exception spam.

---

## PreciseNode 0.7.5

* Fixed erratic textbox behaviour.

---

## PreciseNode 0.7

* Next Encounter now be calculated from the currently selected node.
  * This should fix the issue where the orbit AP/PE was never shown if an encounter
    existed at all.
* Added textboxes for prograde, normal, and radial controls.
* Added a button to focus on the next encounter target.
* Added a button to focus on the active vessel.
* Removed some forgotten debugging symbols.
* Fixed some repaint bugs that may have been causing unexpected CTDs.
* Fixed some null reference bugs through a better node updating scheme.

---

## PreciseNode 0.6

* Added the time to next node in the Clock window if a node is present.
* Added a Trip Info window.
  * Shows the delta-V and time until for the nodes on your route.
  * Totals delta-V for the route.
* Added snap to current orbit peri- and apoapsis buttons for additional UT Controls.
* Now calculating next encounter from the current node forward.
* The "Editing Node" label at the top is now a button that focuses the map view
    on that particular node.
* The Clock window will no longer stay visible when you clear the GUI via F2.

---

## PreciseNode 0.5

* Added ability to open selected maneuver node gizmo via hotkey (default O).
* Added ability to open/hide window via hotkey (default P).
* Added ability to step down increment via alt/option + increment hotkey.
* Added ability to alter the conics patch draw limit.
* Added additional increments for UT manipulation.
* Added an options window for greater user control over plugin:
  * You can show/hide the maneuver node pager.
  * You can show/hide the additional UT controls.
  * You can show/hide the ejection angle.
  * You can show/hide the additional orbit information.
* Added an optional window for conics controls.
  * If enabled the window will show whenever the map view is open.
  * If enabled the window will hide automatically when the main window is open.
* Added an optional clock window to show the current UT and human readable time.
  * If enabled the clock window will always show.

---

## PreciseNode 0.4

* 0.22 compile.
* Added display for node apoapsis and periapsis, or the next encounter periapsis.

---

## PreciseNode 0.3

* Created an options GUI for keymapping.
* PreciseNode will now save the window positions between program executions.
* Changed saving of config file to OnDisable, which happens when you switch flights.
* Changed the time display to add +1 year in order to correct to Space Center time.

---

## PreciseNode 0.2

* Changed the "multiplier" label to "increment".
* Changed increment/decrement button colors away from the terrible cyan and magenta.
* XMLDoc'd all of the functions.
* Added conics mode selectors.
* Added keyboard controls.
* Added saving and loading from config file.