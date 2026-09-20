# The world and the seasons

## The map

Every game is a 64 by 64 tile valley generated from a seed. Three layers of noise decide what each
tile is: elevation, moisture and fertility. Low ground becomes **water**, the highest ground
**mountain** with a skirt of **stone**, wet ground **forest**, rich ground **fertile soil**, and the
rest **grass**.

- Water and mountain cannot be walked on.
- Only grass, forest and fertile soil can be built on.
- The start is a level 7 by 7 clearing at the centre of the map with a stockpile on it.
- Every map is guaranteed at least one mountain with stone around it and walkable ground at its foot,
  so iron and stone are always somewhere, though not always close.

Terrain matters for placement, not only for looks:

| Building | Needs |
| --- | --- |
| Woodcutter, Hunter | Forest within 8 or 12 tiles. The woodcutter fells trees; the hunter does not. |
| Fishing hut, Saltworks | A water tile next to the work tile. |
| Quarry | Stone tiles within 6. |
| Mine | The foot of a mountain within 6. |
| Farm | Anywhere buildable; up to +50 % yield when the 3 by 3 field sits on fertile soil. |

Building never changes the ground. A building stands on a stone plinth that follows the slope
under it, so a hillside stays a hillside. Roads speed walking by 40 %.

## Forest

A forest tile starts with 3 to 6 trees. Woodcutters take them one at a time; hunters leave them.
Each day a thinned forest tile has a 5 % chance to regrow a tree, and a grass tile beside two forest
tiles has a 1 % chance to become forest. Woodcutters placed on a small wood will run out; give them
a large one or several.

## Time

A day lasts 15 real seconds at normal speed. A season is 30 days and a year is 120 days:
spring, summer, autumn, winter. Taxes are collected and the weather is rolled on the first day of
each season.

## Weather

Each season draws one weather for its 30 days. The numbers below multiply cold, firewood burn and
crop growth.

| Season | Weather | Chance | Effect |
| --- | --- | --- | --- |
| Spring | Mild | 6 in 10 | none |
| Spring | Wet | 2 in 10 | crops grow 20 % faster; wet |
| Spring | Late frost | 2 in 10 | cold and firewood 1.5x, crops 0.8x; wet |
| Summer | Fair | 6 in 10 | none |
| Summer | Drought | 2 in 10 | crops 0.5x |
| Summer | Hot | 2 in 10 | crops 1.15x |
| Autumn | Calm | 6 in 9 | none |
| Autumn | Early cold | 3 in 9 | cold and firewood 1.4x; wet |
| Winter | Normal | 6 in 11 | none |
| Winter | Harsh | 3 in 11 | cold and firewood 1.6x; wet |
| Winter | Mild | 2 in 11 | cold and firewood 0.7x |

A **wet** weather is one that spoils what is left out of doors: wood, firewood and planks piled
outside a full store lose 10 per cent of the pile over such a season (see [Economy](economy.md)).
Food rots outside whatever the weather.

## What the seasons do

- **Spring and summer** are the growing seasons. Crops need 45 growing days to ripen, so a field
  planted late in spring may not make it.
- **Autumn** is the harvest. Growth stops; whatever is ripe is brought in. Hearths start burning
  firewood and villagers start to feel the cold.
- **Winter** is the test, and it is the season the land stops. Fields still planted are lost,
  fishing stops, the pasture gives nothing, and a hunter brings back a quarter of his summer catch.
  Cold rises at full speed and every house burns a log a day, more in harsh weather. A month of
  meals and a month of firewood have to be standing in the stores before it starts, and they have
  to be made of something that keeps, because meat and fish go off on the shelf (see
  [Economy](economy.md)).

See [Villagers](villagers.md) for how hunger and cold work, and [Economy](economy.md) for how much
food and firewood a village needs.
