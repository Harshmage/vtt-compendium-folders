# Compendium Folders

This is a module for FoundryVTT which allows you to manage compendiums a bit easier by implementing a folder system.

![](./example.png)

## Instructions
Once the module initially runs, it will convert your existing submenus into folders.
Each folder has 3 icons. Starting from the right
- The Gear icon allows you to edit the compendiums inside a folder. They are grouped by Assigned (already in folders) and Unassigned (not in folders). You can also Delete a folder through this dialog, which will delete all child folders and move all compendiums within to Unassigned
- The Folder icon allows you to create a folder beneath the current folder. 
- The Folder Tree icon allows you to move a folder to another location, also bringing it's children.

You can also import and export your folder configuration, to share with others or to backup your folder structure. In the Settings tab under Compendium Folders you can find an Import/Export dialog. Pasting someone elses Import string into the import box will seamlessly import their folder structure, ignoring any missing compendiums.

I would recommend once you are happy with your layout, to save your folder configuration. This will also be useful if you are going to submit an issue or bug on GitHub.

## Future

1. ~~Move compendiums between folders~~ Now in 0.1.4!
2. ~~Create/Rename/Update/Delete folders~~ Now in 0.1.4!
3. ~~Nesting folders + Moving folders around~~ Now in 1.0.0
4. ~~Seach, collapse all, and refresh (like other tabs)~~ Now in 0.1.7!
5. ~~Import/Export folder configuration~~ Now in 1.0.0!
6. Custom folder ordering (currently defaults to alphabetical)
7. ~~Default folder for new compendiums~~
8. ~~Default open/close state for folders~~
9. ~~Custom folder and icon text color~~ Now in 1.0.6!
10. Drag/Drop functionality
11. Context menu right-click instead of buttons on the folder when open.

Any issues feel free to ping me on Discord (@Erceron#0370)

## Localization
Special thanks to the translators who contributed to this project:
- lozalojo (Spanish)
- CarnVanBeck (German)
- rinnocent (Brazilian Portugese)

## Contribution
If you'd like to support my work, feel free to leave a tip through [my paypal](http://paypal.me/cre463)
