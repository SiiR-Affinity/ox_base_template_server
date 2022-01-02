# OX Base Template Server
This repo contains resources for a "base" ESX server utilizing oxmysql, ox_inventory, NPWD, es_extended (ox version), esx_multichar (ox supported version) as well as many other "base" resources to get you going.

```diff
- THIS IS NOT A FULL SERVER. Only a base to get you started.
+ This package may not get updated often so if you want "bleeding edge" updates you will need to do yourself.
```

With that being said, right out the gate everything will be working/usable but of course configs will need to be tailored to your needs.

[PREVIEW VIDEO](https://www.youtube.com/watch?v=mCVBKO9b_J8)

## MAIN Resources
* [ox_inventory](https://github.com/overextended/ox_inventory)
* [es_extended](https://github.com/overextended/es_extended)
* [esx_multicharacter](https://github.com/thelindat/esx_multicharacter)
* [NPWD](https://github.com/project-error/npwd)
* [fivem-appearance](https://github.com/ZiggyJoJo/brp-fivem-appearance)
* [ev-hud](https://github.com/EntityEvolution/ev-hud)

### EXTRAS
* [qidentification](https://github.com/katotekii/qidentification)
* qidentification has been setup to tie weapon/driver's license item to actual license required by weaponshop for example.
* **norp-vehicles** resource with 1 addon car to show setup for 1 resource for multiple vehicles.
* [mdt](https://github.com/thelindat/mdt) - thelindat fork of hypaste's mdt
* [linden_outlawalert](https://github.com/thelindat/linden_outlawalert) - Per Linden this is broken/needs to be redone (take it or leave it but it does work in some basic scenarios)
* [luke_garages](https://github.com/LukeWasTakenn/luke_garages)
* and a few other various resources and tweaks done by me (Judd#7644)

## IMPORTANT
Make sure to replace the "replaceme" text in server.cfg with your info.

You can also just run FXServer.exe and during setup choose like CFX Default template and after setup
just delete resources created from setup and replace with the resources folder provided.

Similar with the server.cfg you get from setup or just copy and paste from the provided server.cfg

Make sure to change "oxtemplate" in sql file before importing to your db name:
CREATE DATABASE IF NOT EXISTS `oxtemplate` /*!40100 DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci */;
USE `oxtemplate`;

## SUPPORT
I will not be providing support for this. I will try and keep it updated when I can but if you struggle using this then you will struggle with more and you will need to figure out things for yourself. Don't be lazy, google, check cfx forums, ask in discords, etc...

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/P5P57KRR9)
