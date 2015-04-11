# Maya Tangent Switcher

## What/Why:
Animators start by blocking in their poses. To make it a "true" blocking in, you need to have your tangents set to stepped. Unfortunately, setting it to be this way by default means you have to go through and select all your keys later and switch them back to spline so you can get your nice arcs. This became annoying to me, so I wrote this script to automagically change all of the tangents to either linear in/stepped out or spline in and out.

Version Issues:
As far as I know, there are no issues across any of the major platforms (Windows, OSX and Linux). If you note one, file an issue here on GitHub. It's been tested from Maya 2008 - 2011, but it should work across all versions.

## Installation:

### Maya 2010 Instructions:
Copy the tangentSwitcher.mel script into your scripts folder. Open maya and open the script editor and type in:
source tangentSwitcher.mel; tanSwitcher();
Now select that text and go to file -> save script to shelf. Name it and click it and you're good to go!

### Maya 2011 Instructions:
Copy all the files into into your scripts folder (tangentSwitcher.mel and all .ui files). Open maya and open the script editor and type in:
source tangentSwitcher.mel; tanSwitcher();
Now select that text and go to file -> save script to shelf. Select Mel as the type. Name it and click it and you're good to go!

## Notes:
The UI for 2010 is mel based, but the 2011 version is QT based. The QT version definitely looks nicer, but the mel one still functions just the same as it did before (better actually).

## License Information:
This work is licensed under the 3-clause BSD ("New BSD License") license, which has been included.
