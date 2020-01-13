# KipardSkylon
### License: CC-BY-NC-SA
Revived Skylon replica mod for today's KSP.

![Skylon](https://i.imgur.com/x4A0Qq8.jpg)


Originally made and released (open alpha) in December 2014 by kerbal forum user **CaptainKipard** who last appeared mid-2016. [Original thread](https://forum.kerbalspaceprogram.com/index.php?/topic/45790-*/).

## Main Features
* 5m diameter at the midsection. 3.75m engines. Its Payload Bay comfortably holds 2.5m or tightly holds 3.75m.
* Runs on Hydrolox (not LFO) by default: SABRE, OMS/tail engine, Payload Bay's builtin fuel cell and RCS.
* Balanced for 2.7x ~ 3.2x scaled systems. Rated for 30 tons to 600km in 2.7x with its own bay.
* Drone core contains 4 control points: Forward, Up (Docking), SABRE thrust vector, OMS thrust vector.
* Precoolers each create up to 200 Oxidizer per second between Mach 1.2 ~ 6.
* Shock cones animate if **B9AnimationModules** mod is installed.
* SABRE (as per true turborocket nature) sips on Oxidizer in air-breating mode which explains its enduring power in higher atmosphere than most other jet engines.
* Aerodynamics stats thoroughly tested but there's always the inherent issue of the center of lift being under the center of mass due to the wing placement.

## Bonus Features
* Added custom cargo bay for use as a service bay. Can comfortably hold 3.75m and can provide a wide selection of inner node clusters for mounting useful 1.25m things.
* Can sweat Liquid Hydrogen for thermal control/transpiration. (This might not actually be needed.)
* Includes reconfigured, recolored stock wheels to fit its profile.
* Includes some part upgrades.
* Variant themes: Black & White, All Black.
![Skylon Light vs Dark SPH](https://i.imgur.com/4Ohjqab.jpg)

### Dependencies
* [B9 Part Switch](https://github.com/blowfishpro/B9PartSwitch/releases)
* [Community Resource Pack](https://spacedock.info/mod/31/Community%20Resource%20Pack)

### Integrations
* [B9 Animation Modules](https://github.com/blowfishpro/B9AnimationModules/releases) (bundled)
* [WBI Classic Stock](https://github.com/Angel-125/WildBlueTools/releases)

### Issues
Some lasting issues that I've discovered in the process of this takeover include: 
* A drag cube problem with the largest tank pieces. I am not sure if they can be properly fixed. Until then these tanks have an extra stack node added to them and must receive a 3.75m nose cone there. Feel free to hide (but do not scale down) the cones afterward.
* The pre-made wheels run on Firespitter but misbehave even with the current version of Firespitter (as at KSP 1.8.1). While these remain unusuable I have supplied customized stock wheels to use in their place, and hidden them from part select and the R&D facility.
