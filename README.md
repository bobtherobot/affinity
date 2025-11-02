# Affinity Shortcuts
This repo is for those migrating from Adobe Illustrator to Canva Affinity (Serif), and are looking to remap the default Affinity keyboard shortcuts to match what is used in Adobe Illustrator.

While there is no 1:1 mapping, there are some adjustments that can be made to pair the two platforms.

This repo provides a file "Bob-2025-11-22.affshortcuts" you can load into Affinity (Settings > Shortcuts > "Load").

The following adjustments were made. Hopefully others can contribute to this repo to further assist everyone as they migrate.

## Shortcut Modifications

| Adobe       | Affinity | Command (AI) adobe, (AF) affinity |
|-------------|------------------|---------------------------|
| CMD-J       | CMD-D            | (AF) Edit > Duplicate
| C           | C                | (AI) Crop tool
|             | C (removed)      | (AF) Tools > Corner Tool
| Shift-O     | O                | (AF) Tools > Artboard Tool
| CMD-J       |                  | (AI) Join Paths
| CMD-8       | OPT-CMD-8        | (AF) Vector > Create Compound Path
| CMD-8       | SHIFT-OPT-CMD-8  | (AF) Vector > Release Compound Path
| CMD-J       | CMD-J            | (AF) Vector > Node Tool > Join Curve

## Migrating
| Adobe       | Affinity | Command (AI) adobe, (AF) affinity |
|-------------|------------------|---------------------------|
| CMD-7       | Vector Crop Tool | mask
| OPT-CMD-J   | Use Align Panel  | align vertical/horizontal/both


## Additional Info
- Suomy made decent post with more info related to some of the settings used above. [here](https://forum.affinity.serif.com/index.php?/topic/94333-is-there-a-keyboard-shortcut-file-i-can-load-so-that-affinity-designer-has-the-same-shortcuts-as-adobe-illustrator/)
    - NOTES:
        - Edit > Duplicate
            - Illustrator uses CMD-J for "join paths" and CMD-D for "transform again." Affinity Designer contains its "Transform Again" feature as a subordinate function of Duplicate. And some other apps use CMD-D for duplicate.
        - Layer Create / Release Compound
            - Beware: compound paths behave a differently in Affinity than Illustrator. You can achieve the same thing, but there is an extra step to get Illustrator's default behavior. Make a compound, and then select "subtract" in Affinity's layer palette for the item you just compounded. 
        - Tools > Artboard Tool
            - Does not respond to Shift-O like Illustrator. It is just bound to "O" and toggles with the Contour tool
        - Tools > Crop tool
            - This is not a standard tool in Illustrator or a conventional reassignment in Affinity; Made this respond to the "C" tool, and disassociated the corner tool.

NOTE 1: Hide edges. Can't find an equivalent for it in Affinity


## See Also
- [MergeAffinityKeyShortcuts](https://github.com/Pietzcker/MergeAffinityKeyShortcuts)