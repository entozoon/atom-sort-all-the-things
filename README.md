# Sort All The Things - Atom Package

Sorts your lines in Atom, never gets tired.

![sort-lines-demo](https://f.cloud.github.com/assets/2988/1796891/85e69ff2-6a93-11e3-89ac-31927f604592.gif)

### Commands and Keybindings

All of the following commands are under the `atom-text-editor` selector.

If any lines are selected in the active buffer, the commands operate on the selected lines. Otherwise, the commands operate on all lines in the active buffer.

|Keypress|Command|Description|
|--------|-------|-----------|
||`sort-lines:sort`|Sorts the lines (case sensitive)|
||`sort-lines:case-insensitive-sort`|Sorts the lines (case insensitive)|
||`sort-lines:natural`|Sorts the lines (["natural" order](https://en.wikipedia.org/wiki/Natural_sort_order))|
||`sort-lines:reverse-sort`|Sorts the lines in reverse order (case sensitive)|
||`sort-lines:unique`|Removes duplicate lines|
|ctrl-shift-a|`sort-lines:sort-all-the-things`|Sorts the lines naturally and removes duplicates|
