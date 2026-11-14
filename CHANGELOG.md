# Changelog

## 0.2.0
Spawn tooltip shows fluid weight, empty mass, and vehicle dimensions.

## 0.1.0
Smart Piping and Editor Settings Copy are now one mod, Editor QOLs. Each part can be switched off on its own in the
settings. Turn off the old Smart Piping and Editor Settings Copy mods when you install this one.

Smart Piping (from Smart Piping 0.2.2):
- Newly placed pipes connect to the pipes next to them, keeping paint and the editor's undo history.
- Works with the symmetry tool, including pipes that were placed as mirrored copies.
- Drag placement connects neighboring pipes. Hold Left Alt to place without connecting.

Settings Copy (from Editor Settings Copy 0.1.0):
- Copy and Paste buttons in the vehicle editor's top bar for the settings of the selected block.
- Paste only works on a block of the same type. Settings the target shows are filled in, including the
  ones that appear after a type or mode setting changes (for example each instrument of an instrument panel).
- Microcontrollers only accept settings from a microcontroller with the same properties.
- Ctrl+C / Ctrl+V press the buttons while no text field is being edited (keys can be changed in the settings).
- Ctrl+Z / Ctrl+Y undo and redo a paste like any other editor change.
