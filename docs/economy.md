# Economy

The economy is a set of chains from the land to the table. What the realm can hold is what it has
built, and what it has banked when the frost comes decides whether it survives its first winters.

## Resources

| Resource | Made by | Used for | Spoils |
| --- | --- | --- | --- |
| Wood | Woodcutter | every building, firewood, planks, tools | Weathers |
| Firewood | Wood splitter (1 wood into 5) | hearths in autumn and winter, bakery, brewery | Weathers |
| Planks | Sawmill (2 wood into 1) | workshops, barn, civic buildings, house upgrades | Weathers |
| Stone | Quarry | mill, bakery, blacksmith, church, well, house upgrades | - |
| Iron | Mine | tools | - |
| Tools | Blacksmith (1 iron + 1 wood) | one per worker, full work speed | - |
| Leather | Pasture | clothing | - |
| Clothing | Tailor (2 leather into 1) | one per villager, halves winter cold | - |
| Grain | Farm (autumn harvest) | eaten raw, flour, ale | Rots |
| Flour | Mill (2 grain into 2) | bread | Rots |
| Bread | Bakery (2 flour + 1 firewood into 5) | food | Rots |
| Meat | Hunter, Pasture | food | Rots |
| Fish | Fishing hut, spring to autumn | food | Rots |
| Ale | Brewery (2 grain + 1 firewood into 3) | burgher houses, townhouses, tavern | - |
| Salt | Saltworks, all year | townhouses | - |
| Torch | Blacksmith (1 wood + 1 firewood into 2) | carried on campaign: burns gates, walls and halls three times faster | - |
| Battering ram | Sawmill (6 planks + 2 wood into 1, once 40 planks lie in the yard) | pushed to a gate on campaign: brings gates and palisades down five times faster | - |

**Spoils** says what happens to a good left outside a full store. *Rots*: 15 per cent of the
unsheltered pile is lost each season. *Weathers*: 10 per cent a season, but only in wet or harsh
weather. Everything kept under a roof keeps forever; nothing is ever lost inside a store.

## How much a village needs

- **Food**: one meal per villager per day, of any food kind. Storing two or more kinds lifts
  happiness.
- **Firewood**: each house burns a log a day in winter, 0.4 in autumn, and more in cold weather.
  Five houses burn about 60 logs through the autumn and 150 through the winter, on top of what the
  bakery and brewery burn. The steward's line is 15 days a house, so 75 in the pile for five.
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

How much the realm can hold is decided by what you have built. Each store has its own capacity:

| Store | Holds | Under cover |
| --- | --- | --- |
| Stockpile | anything | 500 |
| Barn | food and flour | 600 |
| Granary | grain, flour and bread | 900 |
| Village hall | anything | 150 |
| Market | food, firewood, tools and clothing | 150 |
| Trading post | staged goods | 300 |

Every stockpile, barn and granary also takes **half again as much outside**, as an unsheltered pile
in the yard: a barn holding 600 under its roof takes 300 more in the open. That pile is not safe.
Unsheltered food rots at 15 per cent a season, and unsheltered wood, firewood and planks lose 10 per
cent a season in wet or harsh weather. The hall, the market, the trading post, houses and workshops
have no yard: they fill and stop.

The sheltered space goes to the goods that are worth most work first: bread and flour, ale, salt,
cloth and tools are put under the roof first, then meat and fish, and raw grain, logs, firewood and
planks last, so a full barn puts the raw grain outside before a loaf.

Producers **work into the overflow** and down tools only when the outside pile is full too, or
once the realm already holds six times its keep-at-least line of a good, so one stockpile does not
swallow a summer of wood nobody needs. When that happens the workshop panel says so and the
steward raises "no room left in any store". Before it comes to that you get a warning that goods
are lying outside and spoiling: raise another store.

Carters relieve a settlement whose stores pass **90 per cent** full, moving goods down to 70 per
cent into another settlement that has room, and never below what the first settlement needs itself.

The village aims to keep at least **20 days of food** and **15 days of firewood per house** in
store, measured against the highest population of the last 30 days, so a raid or a hard winter does
not shrink the buffer it is working towards. Below that line the job steward puts more hands on
food and fuel.

Every house also keeps a small larder and woodpile on its shelf, and labourers restock houses from
the stores, so villagers eat and warm up at home rather than walking to the stockpile.

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
