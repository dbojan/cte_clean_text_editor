# cte - clean text editor

2026-09-13-20-27-55

cte - clean text editor for xfce and the like envinronment, created using python + gtk3

![cte](cte.png)


features:

- simple design
- mark pasted text with color (temporarily)
- simple config
- search and replace dialogs don't pick up random text
- autosave
- regex support for search and replace
- use F2 to add timestamp like this: 2026-07-25-20-17-04
- encodings and line endings support
- fixed detached window colors


## changes

2026-09-13-20-27-55
- convert newlines to spaces always remove empty lines first
- added shortcuts f3, shift f3, to search next, search previous.
- added file/reopen file, ctrl+shift+O
- fixed detach window color coding, setting, undo history
- added insert ordinal numbers (1. 2. 3. ..) for selected rows
- fixed bug for last char deletion.
- change order of buttons in search and replace window.

2026-08-11-14-35-06
- added . to indicate encoding and eol

2026-07-30-15-00-37
- added encodings and line endings menu

2026-07-29-14-04-34
- restructured selected menu, added new functions

2026-07-26-22-55-33
- bug fixes around search and replace dialogs

2026-07-23-12-15-08
- removed 'go to line combo box' from 'toolbar icons on by default'
