# samp-anti-cheat

[Original forum thread](http://forum.sa-mp.com/showthread.php?t=504244)

Original Guidelines:

* Patches are to be designed to be included BEFORE YSI
* Patches will contain ALS hooking only
* Patches will contain a callback with the following prefix OnAntiCheat ..... () ex OnAntiCheatAutoAim(playerid)
* Patches will have a description outlining the anticheat
* Patches can use y_iterate

Additional Guidelines:

Since [sampctl](https://github.com/Southclaws/sampctl) is now stable and the [Pawn Package Definition](https://github.com/Southclaws/sampctl/wiki/Packages) is finalised, some additional guidelines related to packages have been added:

* Patches _must_ contain a `README.md` with a description, use `sampctl package init` to generate one
* Patches should be a [Pawn Package](https://github.com/Southclaws/sampctl/wiki/Packages) with all dependencies properly listed
* Patches should contain a `test.pwn` which either contains unit tests or an in-game demonstration runnable via `sampctl package run`
