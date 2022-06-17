# ![Icon](../icon/48x48.png) NB Renamer

## Features

- Preview file name changes interactively
- Inline edit for quick sporadic non-pattern renaming
- Rename by predefined csv file
- Undo/Redo
- Cross platform: Windows/Linux (soon) /MacOS (in future)

Detailed manual [here](./tips.html).

## Releases

- v0.2.3 (2022-06-17)
  - Bug fixes
    - Retry of rename doesn't happen if EPERM error occured on the folder/file
    - When right click file tree and remove a folder from selection, files appear in list even Folders Only ticked
    - When Open Folder, previous renaming parameters are not cleared
  - Disallow mix of files and dirs renaming together

- v0.2.2 (2022-04-08)  
  - New parameters layout
  - Allow backward selection (right-to-left)
  - Move text or a section within the file name
  - Allow to force file names to be case insensitive even the file system is case sensitive
  - General bug fixes and enhancements

- v0.1.2 (2020-09-18)  
  Initial release
