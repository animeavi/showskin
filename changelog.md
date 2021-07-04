vidfk
- added netherite to the items list, hopefully correctly

v5 (this release)

- catch exception on death if armor piece can't be dropped
- stop armor from becoming hidden on first damage
- handle elytra (for real now!) and dragon head

v4

- this changes thanks to JethroCraft from BukkitDev
- added elytra support
- added better shift-click overequipping attempt handling
- some code cleanups and optimizations

v3

- fixed drop saved armor on death, now by writing a dedicated method (now works)

v2

- enchanting levels bugfix
- drop saved armor on all death types (ej.: drowning)

v1

- read/write configuration
- player temporary chests creation (if not exists) on player join
- store/retrieve player armor suit
- command processing ok
- cancel equip armor (player inventory) by click/drag ok
- cancel equip armor by using held item ok (right click)
- cancel equip armor by dispenser
- armor equip for a period (schedule equip armor task)
- damage mitigation by armor recalculed
- equip forever when done by commands
- unequip later when done by events
- recalcule damage mitigation my enchantmets, falling anvil, fall damage
- armor status messages

TODO

- detect when player is looking a right-clickable block/entity
- work with uuid to avoid armor loss/steal on player change name
- work internally with uuid to increase stability
- optionally equip armor on touch water having underwater enchantments
- drop the need of having "physical" chests, by saving serialized items on yml
- play a (cracking) sound alert on armor durability changes
- update damage calculations

