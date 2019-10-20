# PiggyCustomEnchants [![Poggit-CI](https://poggit.pmmp.io/ci.badge/DaPigGuy/PiggyCustomEnchants/PiggyCustomEnchants/master)](https://poggit.pmmp.io/ci/DaPigGuy/PiggyCustomEnchants) 

PiggyCustomEnchants is an open-sourced custom enchants plugin for PMMP.

## v2.0.0 changelog
Version 2.0.0 is a complete rewrite of the plugin and introduces tons of bug fixes, optimizations, and quality of life changes.
All custom enchantments in Version 1.4.6 have also been ported to Version 2.0.0.

* Enabling/disabling enchantments in certain worlds/globally is now built into the plugin. (#94)
* Custom enchantments that are disabled will not have their tasks enabled.
* Explosive enchants now have a toggle to allow world damage or not.
* Custom enchantments are now registered into PocketMine-MP.
* Added a remote-enchant disabler for emergency situations (disable affects all servers).
* "Maximum -5 is less than the minimum 0" issue has been fixed. (#211)
* Fixed "WitherSkull Enchant does not apply Wither Effect." (#182)
* Fixed issue where throwing a projectile and switching to CE weapon would apply the effects of the CE weapon to the player. (#157)
* Fixed pigs/wither skulls remaining. (#189)
* And... introduced new undiscovered bugs.

<!-- If one question constantly persists, add the Q/A in here. -->
## FAQ
**Q:** How do I create/use an enchanted book? </br>
**A:** If you want to create an enchanted book, use the /ce enchant command on a normal book. Afterwards, you place the item you want to enchant on top of the enchanted book. It will then enchant your item.

**Q:** `ErrorException: "Invalid argument supplied for foreach()" (EXCEPTION) in "plugins/PiggyCustomEnchants.phar/src/DaPigGuy/PiggyCustomEnchants/PiggyCustomEnchants" at line 54`</br>
**A:** This is due to an outdated configuration from Version 1.0.0. You should delete your old configuration to allow PiggyCE to re-generate a new configuration.

## Information
* We do not support any spoons. Anything to do with spoons (Issues or PRs) will be ignored.
* You can find a list of the current custom enchants at [wiki](https://piggydocs.aericio.net/PiggyCustomEnchants.html).
* We are using the [libFormAPI](https://github.com/jojoe77777/FormAPI), so there is no need to install the FormAPI plugin.
    * In other words, you must use the pre-compiled phar from [Poggit-CI](https://poggit.pmmp.io/ci/DaPigGuy/PiggyCustomEnchants/~) instead of GitHub.
    * If you wish to run it via source, check out [DEVirion](https://github.com/poggit/devirion).
* Are you a developer? Check out our API Documentation at [PiggyDocs](https://piggydocs.aericio.net/PiggyCustomEnchants.html).
    * v2.0.0 list of custom enchants are also at PiggyDocs.
* Check out our [Discord Server](https://discord.gg/qmnDsSD) for additional plugin support.
