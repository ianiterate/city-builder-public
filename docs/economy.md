# Economy

The economy is a set of chains from the land to the table, with a few hard limits that decide
whether the village survives its first winters.

## Resources

| Resource | Made by | Used for | Store limit |
| --- | --- | --- | --- |
| Wood | Woodcutter | every building, firewood, planks, tools | 250 |
| Firewood | Wood splitter (1 wood into 5) | hearths in autumn and winter, bakery, brewery | 600 |
| Planks | Sawmill (2 wood into 1) | workshops, barn, civic buildings, house upgrades | 30 |
| Stone | Quarry | mill, bakery, blacksmith, church, well, house upgrades | 100 |
| Iron | Mine | tools | 40 |
| Tools | Blacksmith (1 iron + 1 wood) | one per worker, full work speed | 30 |
| Leather | Pasture | clothing | 40 |
| Clothing | Tailor (2 leather into 1) | one per villager, halves winter cold | 30 |
| Grain | Farm (autumn harvest) | eaten raw, flour, ale | 600 |
| Flour | Mill (2 grain into 2) | bread | 100 |
| Bread | Bakery (2 flour + 1 firewood into 5) | food | 400 |
| Meat | Hunter, Pasture | food | 250 |
| Fish | Fishing hut, spring to autumn | food | 400 |
| Ale | Brewery (2 grain + 1 firewood into 3) | burgher houses, townhouses, tavern | 120 |
| Salt | Saltworks, all year | townhouses | 60 |
| Torch | Blacksmith (1 wood + 1 firewood into 2) | carried on campaign: burns gates, walls and halls three times faster | 30 |
| Battering ram | Sawmill (6 planks + 2 wood into 1, once 40 planks lie in the yard) | pushed to a gate on campaign: brings gates and palisades down five times faster | 2 |

The store limit is the most of a resource the realm keeps; production pauses at the limit so
workers do not fill the stores with one thing.

## How much a village needs

- **Food**: one meal per villager per day, of any food kind. Storing two or more kinds lifts
  happiness.
- **Firewood**: each house burns about a log a day in winter, 0.4 in autumn, and more in cold
  weather. A village of five houses wants roughly 40 to 50 logs banked before winter, on top of
  what the bakery and brewery burn.
- **Tools**: one per adult worker. A worker without one works at half speed. A tool wears out after
  about 80 days of work.
- **Clothing**: one per villager, lasting three years. Without it cold rises half again as fast.

The stewards' warnings (see [Alerts](alerts.md)) fire at six days of food or firewood left and
again at two.

## Gathering

| Job | Yield | Notes |
| --- | --- | --- |
| Woodcutter | 4 wood per trip | fells the tree; forests regrow slowly |
| Hunter | 5 meat per trip | leaves the forest standing |
| Fisher | 4 fish per trip | not in winter |
| Quarrier | 2 stone per trip | needs stone tiles |
| Miner | 1 iron per trip | needs a mountain foot |
| Salter | 2 salt per trip | needs water, works all year |

Each of these huts takes two workers. A **farm** is a 3 by 3 field with one farmer: planting takes
work in spring, the crop needs 45 growing days, and the harvest in autumn is up to 36 cycles of
7 grain, half again as much on fertile soil. A field still standing when winter begins is lost.
A **pasture** is a 3 by 3 plot giving 3 meat and 1 leather per cycle with no input.

## Stores and larders

The **stockpile** (500 units, anything) is the village's first store. A **barn** (600) holds food
only. The hall, market and trading post also store goods. Every house keeps a small larder and
woodpile on its shelf, and labourers restock houses from the stores, so villagers eat and warm up
at home rather than walking to the stockpile.

Stock counts are **realm wide**: the top bar shows everything in every store in every settlement.
Goods move between settlements by cart. A settlement may only send away what it holds above its own
need, and when one village runs short while the realm has plenty, the steward names it in a "local
larder" or "local woodpile" warning rather than a general shortage.

## Trade

A **trading post** brings a merchant every 30 days for an 8-day stay (every 15 with a trade pact).
Each visit offers four goods drawn from tools, clothing, iron, stone, grain, planks, leather and
firewood. You buy at 1.5 times a good's value and sell at 0.6 times it.

Standing rules per good let trade run itself: *sell above* a threshold, *buy up to* a threshold, or
ignore. Only goods staged at the post (at most 60 per kind) can be sold, and two floors are never
crossed: food never sells below 15 days of meals and firewood never below 30 logs per house.

## Taxes and the treasury

Taxes are collected on the first day of each season at a rate you set from 0 to 3. Each housed
adult pays 2 gold per tax level, times 1 in a house, 2 in a burgher house and 3 in a townhouse.
Each tax level costs 0.08 happiness. Gold buys from the merchant, pays gifts and pacts to the rival
houses, buys off raiders, and funds campaigns (see [Regions and rivals](regions-and-rivals.md)).

## Upkeep of the higher tiers

A burgher house wants one ale per adult every 12 days; a townhouse wants that plus one salt every
20 days. A house pays from its own shelf, so the brewery, saltworks and the labourers who restock
houses all have to keep up. Unmet days pull happiness down; met days lift it. See
[Buildings and town tiers](buildings-and-tiers.md).
