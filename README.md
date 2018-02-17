# zcommon.acs for Zandronum
This repository contains the latest version of zcommon.acs for Zandronum that includes the latest Zandronum-specific functions. To download, click "Clone or download" above and then "Download as ZIP".

Also, `floor()`, `ceil()` and `round()` are renamed to `ZDoom_floor()`, `ZDoom_ceil()` and `ZDoom_round()`. Why? Because they [return 0 in all versions of Zandronum](https://zandronum.com/tracker/view.php?id=3155), and [ACSUtils](https://github.com/Korshun/acsutils/) already includes their implementations that work in Zandronum. You can [copy them](https://github.com/Korshun/acsutils/blob/master/src/acsmath.acs#L118) from ACSUtils if you don't want to use the whole ACSUtils.

## Supported compilers
* ACC - see `acc/` folder
* BCC - use ACC files to compile ACS with BCC, see `bcc/` folder for BCS language version
* GDCC - see `gdcc/` folder

