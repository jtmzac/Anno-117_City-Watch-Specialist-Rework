# City Watch Specialist Rework
Changes city watch specialists to affect all of their respective building types on the island and gives each building a small area buff of the relevant type (fire safety/health/happiness).

In addition to the small buff, rare specialists also add an additional patrol while epic ones add a patrol and an additional buff depending on the watch type.

The buff values may be wildy unbalanced depending on difficulty settings and other factors such as city status debuffs and building density. I've tried to set default values that are on the lower side to prevent them being too ridiculous.

## Fire Safety/Health/Happiness Buff Values for Each Rarity
| Rarity     | Default |
| -------    | -------   |
| Common     | 0.3   |
| Rare       | 0.6   |
| Epic       | 1.0    |

## Compatibility with Specialist Pools Rebalance
If you use my other mod that removes these specialists by default (Specialist Pools Rebalance) then they will be re-added to the pool at the non-Roman trader in Albion (Manx)

## Customisation
If you do not like the provided values then to change them please edit the appropriate sections in the mods assets.xml.

The file is rather long due to the needed xml structure but there is 3 values for each of the FireSafety, Health and Happiness.

I've checked and you should be able to safely do a find and replace for the existing values of 0.3, 0.6 and 1.0. Just don't forget the .0 on the 1.0

You may need to remove and re-add the specialists to your officium/villa to apply new values
