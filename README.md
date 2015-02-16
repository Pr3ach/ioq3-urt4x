# ioQ3 for UrT42
ioQ3 engine modifications for Urban Terror 4.2.021.

## Server

### Commands
* Server command `setweapon <player> <weapon> <[+|-|]optional_clips> <[+|-|]optional_ammo>` Give a weapon to a player, and if opt param used, set or add/rm (+|-) clips/ammo.
* Server command `rmweapon <player> <weapon|*>` Remove a player's weapon or all of them.
* Server command `teleport <src_player> <dest_player>`
* Server command `setstamina <player> <[+|-|]stamina_percent>` Set or add/rm (+|-) stamina percent to a player.
* Server command `setkills <player> <[+|-|]kills>` Set or add/rm (+|-) kills to a player.
* Server command `setdeaths <player> <[+|-|]deaths>` Set or add/rm (+|-) deaths to a player.
* Server command `su <player> <cmd> [<opt_arg0> <opt_arg1> ...]` Makes a player execute a command.
* Server command `giveitem <player> <item>`
* Server command `rmitem <player> <item|*>` Remove a player's item or all of them.

### Cvars
* `sv_infStamina <0|1>` Allow for infinite stamina.
* `sv_infWalljumps <0|1>` Allow for infinite walljumps.
* `sv_noRecoil <0|1>`
* `sv_showKickMsg <0|1>` Enable/disable showing kick reason to every players.

## Client

## Details
* weapon names: knife, beretta, de, spas12, mp5, ump45, gl, lr300, g36, psg1, he, smoke, sr8, ak103, bomb, negev, m4, g18, colt, mac11
* item names: redflag, blueflag, neutralflag, vest, medkit, silencer, laser, helmet, bomb, ammo, c4

## Support
For anything else, see 'README' at the repo root. You can also report any bug or suggestions by simply opening an issue here.

