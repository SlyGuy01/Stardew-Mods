
---Configuartion Settings Explained---


After launching Stardew Valley with the mod installed for the first time, a config.json file will be created in the mod's folder. 
Open this file to find the following settings:

  "Accessories": "true",
  "Hats": "true",
  "Hairstyles": "true",
  "HairHue": "2",
  "Shirts": "true",
  "Sleeves": "short",
  "FarmerBaseChanges": "true",
  "ExternalFarmerBaseChanges": "false",
  "ShoeColors": "true",
  "SkinColors": "true"

Switch "true" to "false" to enable or disable specific features. If using another mod affecting the same assets, consider disabling 
conflicting features here. Changes will not take effect until after restarting the game. Even with the “Mod Generic Config Menu,” 
changes require the game to restart.


Hair Hue Values:
For hair hue, choose from three options:
    "1": Brightest
    "2": Medium brightness
    "3": Slightly darker (vanilla shades)
These values only affect this mod's hair styles.


Sleeves:
Shirt sleeves can be set to either "short" or "long" regardless of the shirts being enabled/disabled. Changing sleeve length also 
requires a game restart, unless updated in the future.


---FarmerBaseChanges Settings---


These settings enable/disable changes to the farmer base sprite (farmer's body). Note that you can't mix and match changes to the 
farmer base sprite with other mods.

    FarmerBaseChanges: This setting determines whether changes to the farmer's base sprite from this mod are enabled or disabled. 
    Setting it to "true" enables the modifications provided by this mod.

    ExternalFarmerBaseChanges: This setting determines whether changes made by other mods to the farmer's base sprite are enabled 
    or disabled. Setting it to "true" allows other mods' modifications to take effect.


If you prefer another mod's changes, like "no nose" in "Seasonal Outfits - Slightly Cuter Aesthetic", adjust your settings accordingly:
    "FarmerBaseChanges": "false",
    "ExternalFarmerBaseChanges": "true"

To use the modified sprite from this mod:
    "FarmerBaseChanges": "true",
    "ExternalFarmerBaseChanges": "false"

To use the default vanilla sprite:
    "FarmerBaseChanges": "false",
    "ExternalFarmerBaseChanges": "false"


Enjoy your gameplay!
