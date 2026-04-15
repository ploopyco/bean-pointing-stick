## Only one file? Where are the parts?

The STEP/STL files contain all of the plastic parts in one file. Doing it this way preserves the assembly information, showing how the parts are supposed to fit together, as well as the expected clearances between parts. It also bundles all of the parts for a given revision together, so there's no accidental mixing of parts from different revisions.

## How do I print this?

You'll need to split the parts in the file up before you can print them. Most slicers can do this; if you have a compatible printer we recommend PrusaSlic3r, since that's the one we use in-house and have checked.

Note that submitting this file to some 3rd party print services will cause confusion, as they are expecting one body instead of many. To do this, you can use PrusaSlic3r to split the parts and then export each separately as an STL.

## Why don't you include a .gcode file?

For your safety. Uploading a .gcode file onto a printer can be extremely hazardous if that .gcode file wasn't specifically generated for that printer. We don't want to come anywhere near that sort of scenario, so we are not going to upload a .gcode file.