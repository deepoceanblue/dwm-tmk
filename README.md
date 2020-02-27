# DWM-TMK

My fork of dwm by (suckless.org)[dwm.suckless.org].

Here I experiment with different patch combinations and settings.
Subject to constant change.

The structure is:

- master: for now keep pristine, as a reference for new branches

- \<patchname>: each patch has its own branch and is applied at clean copy of master. 
Once patch is applied, and corrections are made, it should not be changed.
 
- config-changes: patches are very inconsistent if/where to auto-apply changes to keybindings, const etc. (config.def.h, config.h, nowhere). 
This branch is dedicated to keep track of all such changes, and to make sure these are propagated to my config.h.  

- MERGE[0-9][0-9]: here merging of different patch combination happens.
 There might be more than one MERGE branch at a time, each for different patch combination.
 MERGE branches are often changed, reset or discarded.
 
The commit message should always indicate instances of manual application/conflict resolution.
