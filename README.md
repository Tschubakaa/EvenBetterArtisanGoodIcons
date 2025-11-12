# Even Better Artisan Good Icons

An updated mod fix to Better Artisan Good Icons (originally created by danvolchek).
[Github Link](https://github.com/danvolchek)
[NexusMods Link](https://next.nexusmods.com/profile/CatCattyCat)

[Original Mod Link](https://www.nexusmods.com/stardewvalley/mods/2080)

## How to Download
Click on the [Link](https://github.com/chsiao58/EvenBetterArtisanGoodIcons/releases/tag/v1.6.6) or go to the release page.  
Then download the file named **EvenBetterArtisanGoodIcons.1.6.6.zip**.  

You don’t need anything else if you are just a normal user.

## How it works

The mod overwrites the corresponding draw functions for artisan goods using [Harmony](https://github.com/pardeike/Harmony), and then draws the right texture for them based on what was used to make them. 

Note that this repo does not contain the Harmony dll.

## For user

For the ease of maintaining this mod, the unique id of this mod was updated to **haze1nuts.evenbetterartisangoodicons**.

To use other content pack that is created for original BAGI along with this base mod, please replace the content pack dependency from **cat.betterartisangoodicons** to **haze1nuts.evenbetterartisangoodicons**, in the content pack's manifest.json.

## Mead support

This framework supports Meads from other mods that are based on flower honey.  
Only Meads using the vanilla Mead **ID (459)** are recognized.  
Multi-ingredient or combined Meads are not supported.

### Tested and working Mead mods
- Flower Meads  
- Better Honey Mead

## Future Update

* Combability fix for mods that add new base ingredients.
* Wild Honey and Sunflower Honey fix
* Generic Mod Config Menu support
* Mod optimization
* Code support for Aged Roe