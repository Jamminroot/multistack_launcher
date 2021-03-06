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