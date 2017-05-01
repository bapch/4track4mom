# 4track4mom

Attempt at creating a 4-track recorder as a companion for C&G Organelle mother patch.

## Features completed
* Read 4 mono tracks (6m20s each -2^24smp@44.1kHz- maximum length without varispeed)
* record 1 track while reading the 3 others
* scrubbing to a bar:beat:ms or to min:sec:ms
* punch recording : mark start point and end point

## TODO
* embeddable in mother.pd
* controllable via messages / OSC from child patch
* automation for volume and pan
* panning
* copy/paste/delete/duplicate
* metronome (continous and preroll)
* save/recall/delete session
* export as 4 separate tracks
