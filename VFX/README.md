# VFX Tweaks

## Disable Hazard Transition effect

To turn of transition effects on harzards I could only get the effect I want by changing the spawn radius to a large number. Works on enter or exit

* game/vfx/vfx_environment/gen_hazards/hazardarealeave/effect/fx_hazardarea_exit
* Change SpawningRadius = to a very large number e.g. 10000000
