# zcommon.acs for Zandronum
This repository contains the latest version of zcommon.acs for Zandronum that includes the latest Zandronum-specific functions

Also, `floor()`, `ceil()` and `round()` are renamed to `ZDoom_floor()`, `ZDoom_ceil()` and `ZDoom_round()`. Why? Because they return 0 in all versions of Zandronum, and [ACSUtils](https://github.com/Korshun/acsutils/) alrready includes their implementations that work in Zandronum.
