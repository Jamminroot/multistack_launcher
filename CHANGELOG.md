## 1.6.0.0
- **NEW** Added an option to disable git updates and UI
- **NEW** Added new theme (dark colors, with respect to Windows accent color)
- **NEW** Added an option to clear search bar upon app launching
- **NEW** Version upgrades
- **FIX** Minor changes
- **NEW** **IMPORTANT** Changed the icons package, so now it's required to re-configure the icons for the stacks. Sorry for the inconvenience.

## 1.4.1.0
- **FIX** Fixed UI bug when editing active tag
- **FIX** Fixed bug which did not allow to add new projects on a fresh install
- **NEW** Version upgrades

## 1.4.0.0
- **FIX** Fix windows 11 compatibility issue (found on dev\beta channels)
- **NEW** Updated Flutter version to 2.10.4

## 1.3.2.0
- **FIX** Notes: Fix note contents height
- **FIX** Notes: Fix tab text updates on title changes
- **CHANGE** Notes: Changed look and position of `Close` (aka "back") button - now it's in the top-left corner, and is just an arrow
- **FIX** Fix duplicates creation upon project edit
- **FIX** Project editor overflow - added scroll to the dialog
- **NEW** Updated Flutter version to 2.9.2

## 1.3.1.0
- **FIX** Fix settings not loading bug

## 1.3.0.0
- **NEW** `Enter` key will now launch default stack (if it is assigned)
- **NEW** Ability to assign a default stack to then later launch it with `Enter` key

## 1.2.2.0
- **FIX** Fixed addition of new projects (placed missing button back)
- Happy new year!

## 1.2.1.0
- **NEW** `Escape` key now clears the filter text

## 1.2.0.0
- **NEW** Added notes support to the projects (for taking quick notes relevant to projects)
- **BREAKING CHANGE** Data storage format changed to *.json, so one would have to either re-configure projects and stuff, add `.json` extension to files under `%APPDATA%\youdev.ru\multistack_launcher\` (including all sub-folders)