# ioQ3 for UrT42
ioQ3 engine modifications for Urban Terror 4.2.023.

## Server

### Commands
* Server command `setweapon <client> <weapon> <[+|-|]optional_clips> <[+|-|]optional_ammo>` Give a weapon to a client, and if opt param used, set or add/rm (+|-) clips/ammo.
* Server command `rmweapon <client> <weapon|*>` Remove a client's weapon or all of them.
* Server command `teleport <src_client> <dest_client>` Teleport src_client to dest_client.
* Server command `setstamina <client> <[+|-|]stamina_percent>` Set or add/rm (+|-) stamina percent to a client.
* Server command `setkills <client> <[+|-|]kills>` Set or add/rm (+|-) kills to a client.
* Server command `setdeaths <client> <[+|-|]deaths>` Set or add/rm (+|-) deaths to a client.
* Server command `su <client> <cmd> [<opt_arg0> <opt_arg1> ...]` Makes a client execute a command.
* Server command `giveitem <client> <item>` Give an item to a client.
* Server command `rmitem <client> <item|*>` Remove a client's item or all of them.
* Server command `invisible <client>` Toggle client invisibility.
* Server command `chversion <version_string>` Changes the version cvar.

### Cvars
* `sv_stamina <0|1|2>` 0 = normal, 1 = insta-regen, 2 = infinite.
* `sv_infWalljumps <0|1>` Allow for infinite walljumps.
* `sv_noRecoil <0|1>` Enable/disable weapon recoil.
* `sv_verbose <0|1>` Enable/disable message to everyone on some actions (eg. radio disabled)
* `sv_allowRadio <0|1>` Allow/disallow the use of radio.
* `sv_allowJoin <0|1>` Allow/disallow joining red/blue from spec/free.
* `sv_allowSpec <0|1>` Allow/disallow joining spec.
* `sv_allowSwitch <0|1>` Allow/disallow team switching.
* `sv_allowSuicide <0|1>` Allow/disallow clients from committing suicide.
* `sv_allowChat <0|1>` Allow/disallow global chat.
* `sv_allowTeamChat <0|1>` Allow/disallow team chat.
* `sv_minKillHealth <0-100>` Disallow killing when your health is below.
* `sv_minTeamHealth <0-100>` Disallow team switching when your health is below.
* `sv_hideCmd <0|1>` Enable/disable hiding cmds (for bot etc.).
* `sv_rmKnife <0|1>` Allow/disallow knife.


## Client

## Details
* weapon names: knife, beretta, de, spas12, mp5, ump45, gl, lr300, g36, psg1, he, smoke, sr8, ak103, bomb, negev, m4, g18, colt, mac11
* item names: redflag, blueflag, neutralflag, vest, medkit, silencer, laser, helmet, bomb, ammo, c4

## Support
For anything else, see 'README' at the repo root. You can also report any bug or suggestions by simply opening an issue here.

