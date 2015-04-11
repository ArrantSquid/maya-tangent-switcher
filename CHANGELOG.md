Maya 2011 Changelog for 2.7:
2.7

- changed some procedures to be able to integrate with QT Interface
- updated UI for Maya 2011 using QT
- changed the default of spline tangents to flat which reduces penetration of ground plane issues
- added a button to launch the Graph Editor and the Dope Sheet Editor
- fixed a bug with multi-selection
- now use shift to select multiple items
- double click to deselect all items
- added ability to re-order items in the list for character sets
- added version checker
- cleaned up TONS of code
- added better comments to the code
- reformatted the code because it was ugly as hell
- took license information out of the script since it's now included as part of the download

Maya 2010 Changelog for 2.7:
2.7

- changed some procedures to function better
- changed the default of spline tangents to flat which reduces penetration of ground plane issues
- added a button to launch the Graph Editor and the Dope Sheet Editor
- fixed a bug with multi-selection
- added version checker and popup for 2011 users using the 2010 script
- cleaned up TONS of code
- added better comments to the code
- reformatted the code because it was ugly as hell
- reorganized code for better readability
- took license information out of the script since it's now included as part of the download

Previous Versions Changelog:
2.6

- changed some procedure names and variables
- cleaned up some code

2.5

- redid the layout so it made more sense
- cleaned up the code a bit
- renamed some procedures and reduced rendundancy

2.4

- fixed another nasty bug that made it so that if you had two characters in a scene and you selected a character's character set and changed the tangent and then selected another character set (from either the same character or another), both would inherit the last tangent command given. this was because multi-select is enabled and the selection was not being cleared after the tangents were changed.
- fixed a bug where time was being taken from the entire timeline rather than the current timeline's minimum and maximum values. now if you simply set your options for your timeline like you normally would it will only affect those keyframes.
- removed a menu option so that users would just get the window that they needed rather than prompting them to choose one.

2.3

- fixed a nasty UI bug that disallowed os x users the pleasure of using this script (and since I use os x it kinda matters to me)
- changed the line endings to be -NIX compatible (since Windows is idiotic about how it handles line endings)

2.2

- added about and help buttons
- finished adding option for simple and advanced interfaces

2.1

- began adding simple and advanced features

2.0

- added in options to allow users to choose their in and out tangent types
- cleaned up code
- almost completely re-written, thus the reason for a full version jump

1.2

- added new windows for easier use by average users
- added in a non-character set version
- renamed some procedures to avoid conflicts
- renamed some windows to avoid conflicts

1.1

- rewrote almost from scratch
- removed "update" button
- made character sets load by default
- fixed bug where multiples of the same character sets were listed
- unbroke entire script
- removed useless and/or redundant code
- added code to delete the windows

1.0

- added more buttons to make process easier
- broke entire script
- made window smaller

0.5

- fixed "stepped" option to be stepped and not clamped
- made option to go back to spline instead of linear
- added full gui
- various minor fixes

0.1

- improved snappiness
- made option to go back to linear tangents
- fixed variable errors
