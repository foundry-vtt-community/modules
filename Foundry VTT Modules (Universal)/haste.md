## Haste

* **Author**: grape_juice#2539 on Discord.
* **Version**: 0.4.9
* **Foundry VTT Compatibility**: 0.6.0+
* **Module Requirement(s)**: None
* **Module Conflicts**: None
* **Translation Support**: EN

### Link(s) to Module
* [https://gitlab.com/jesusafier/haste](https://gitlab.com/jesusafier/haste) 
* [https://gitlab.com/jesusafier/haste/-/raw/master/module.json](https://gitlab.com/jesusafier/haste/-/raw/master/module.json)

### Description
An experimental performance enhancement tweak modules for FoundryVTT it has 2 features:

- Wall fix - patches the FOW LOS FOV calculation to be much more efficient using spatial grid calculations. Big words that mean performance is basically unchanged when running 4000+ walls and 50+ light sources on large scenes.
- Adaptive GPU FPS - Stops the canvas redraws when no changes occurred in the scene, reduces GPU usage to 0% unless a token moves or the canvas is panned. Best used when disabling cursor pointers. When using this options you can set the FPS limiter to 60fps.

---

