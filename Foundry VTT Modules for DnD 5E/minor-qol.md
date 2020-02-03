## Minor QOL Improvements

* **Author**: @tposney#1462 on Discord
* **Version**: 0.18
* **Foundry VTT Compatibility**: 0.4.4+
* **System Compatibility (If applicable)**: dnd5e 0.8
* **Module Requirement(s)**: None
* **Module Conflicts**: Does not work with the default Apply damage pull down but provides chat damage buttons instead.
* **Translation Support**: English, but localization support is included.

### Link(s) to Module
* https://gitlab.com/tposney/minor-qol/master/minor-qol
* [https://gitlab.com/tposney/minor-qol/raw/master/minor-qol.zip](https://gitlab.com/tposney/minor-qol/raw/master/minor-qol.zip)
* [https://gitlab.com/tposney/minor-qol/raw/master/module.json](https://gitlab.com/tposney/minor-qol/raw/master/module.json)

### Description
 Link: https://gitlab.com/tposney/minor-qol
Manifest:  https://gitlab.com/tposney/minor-qol/raw/master/module.json

Please see the link for more detailed info.

* A confirmation dialog when you delete an item from the character sheet
* The ability to add damage buttons to any standard dnd5e damage dice roll.
* Speed Rolls. There are quite a few options, but simply when you enable the flag "Speed Item Rolls" the item roll icon (on the character inventory) allows you to use shift/ctrl/alt for standard rolls (if you don't select any then the default chat card will be displayed), rolls with disadvantage and advantage respectively. So for normal usage you shift click the weapon/spell icon to do a normal speed roll.
* Speed item rolls support rolling the attack, checking if the attack hit the target, any saves, the damage and applying the damage if the attack hits all automatically (taking into account damage immunities for single damage type rolls). You can decide how much automation you want, toggling off auto hit checking, auto saves and damage application. 
* You can choose display the target token's name or it's image in the save/hits chatcards. 
* When applying damage the module uses targeted opponents not selected.
* For weapon attacks only the fist targeted token is damaged by the attack. 
* If casting an area affect spell target all of the affected tokens.
* The module also supports speed item rolls on the macro bar. 
* You can create speed item macro rolls by hand, create a script macro and enter 
```MinorQOL.doMacroRoll(event, "Greataxe")```

* The attack/damage rolls are displayed using the system chat cards.
* You can enable roll buttons on the inventory sheet.
* The module will speed cast spells at the default level and consume the appropriate spell slot or auto use a higher level slot.  Spell scaling will be applied. Useful for pact/always prepared spells which will consume slots from the main spell slots. Innate spells don't.

Many thanks to @Red Rein @Hooking for allowing me to pillage their code.

---

