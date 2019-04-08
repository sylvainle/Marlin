# Marlin 3D Printer Firmware 1.1.9 for ender 5 (motherbard v1.1.4)

## Why switch to 1.1.9 ?

The ender 5 comes with a 1.1.6 marlin firmware and few software issues :
- No "out of bounds" software security
- No probe fail software security
- X and Y reversed in UI (xmin and ymin on right/top)
- Many features are not available on the printer LCD (ie : bed leveling)
- Space between xy cars and endstop switches is small so each xy autohome cause a collide with the frame (could damage the printer over time)

Actually, switch to a newer merlin 1.1.9 firmware is not the bigger thing. Main goal is to enable features and tweak options in order to solve issues.

## Does it solve all issues ?

Almost... speed is now reduced during xy autohome but this is a mitigation. A hardware fix is required about this issue (ie https://www.thingiverse.com/thing:3349425).
