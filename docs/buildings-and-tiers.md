# Buildings and town tiers

## Placing a building

Pick a card from the build bar and click the ground, or drag the card onto the map. The ghost is
green where the building fits and red where it does not; the info box says why. The tool stays in
hand so you can place several; Escape or a right click puts it away. Roads are painted by dragging
and cost nothing. Palisades are drawn as a run.

A placed building is a **site**. Labourers carry its materials to it, then builders work on it until
the build work is done. A site can be **paused** from its panel: nothing more is carried in and
nobody works there, but what was delivered stays. There is also a global "down tools" toggle. A
builder who arrives hungry or cold still puts in one unit of work before leaving, so a far site
never stalls forever.

**Dismantling** takes two clicks within four seconds. A finished building gives back half its
build cost, rounded down per material; a site gives back everything already carried to it, and
so does an upgrade in progress. The goods go to the storehouses that have room and the rest is
lost - the toast tells you which. Walls and gates refund the same way.

## The buildings

Cards are grouped in tabs: Housing, Storage, Gathering, Farming, Crafting, Civic, Military and
Roads. Each building unlocks with a goal card (see [Goals and the steward](goals-and-the-steward.md));
in free build everything is open from the start.

| Building | Size | Cost | Workers | What it does |
| --- | --- | --- | --- | --- |
| Stockpile | 2x2 | 8 wood | 1 carter | stores 500 of anything, plus 250 outside in the open |
| Woodcutter's hut | 2x2 | 10 wood | 2 | wood from forest within 8 |
| House | 2x2 | 16 wood | | 4 beds, a larder and a hearth |
| Hunter's lodge | 2x2 | 12 wood | 2 | meat from forest within 12 |
| Wood splitter | 2x2 | 10 wood | 2 | 1 wood into 5 firewood |
| Fishing hut | 2x2 | 12 wood | 2 | fish, needs water beside it, not in winter |
| Farm | 3x3 | 6 wood | 1 | grain, harvested in autumn |
| Barn | 3x2 | 20 wood, 6 planks | | stores 600 of food and flour, plus 300 outside where it rots |
| Well | 1x1 | 8 stone | | +0.05 happiness within 8 |
| Pasture | 3x3 | 16 wood | 1 herder | meat and leather; the herd can be culled for 20 meat and 5 leather, then idle 60 days |
| Palisade | 1x1 | 2 wood | | a wall piece, 60 hit points |
| Gate | 1x1 | 4 wood | | a wall piece people can pass, 40 hit points |
| Quarry | 2x2 | 12 wood | 2 | stone from stone tiles within 6 |
| Sawmill | 2x2 | 14 wood | 1 | 2 wood into 1 plank |
| Market | 3x3 | 24 wood, 10 planks | | stores 150, +0.10 happiness within 14, the burgher civic |
| Barracks | 3x2 | 24 wood, 8 planks | 4 militia | trains the militia |
| Mill | 2x2 | 10 wood, 10 planks, 6 stone | 1 | grain into flour |
| Bakery | 2x2 | 8 wood, 8 planks, 10 stone | 1 | flour and firewood into bread |
| Granary | 3x2 | 24 wood, 8 planks, 6 stone | | stores 900 of grain, flour and bread, plus 450 outside |
| Blacksmith | 2x2 | 8 wood, 6 planks, 12 stone | 1 | iron and wood into tools |
| Mine | 2x2 | 16 wood, 6 planks | 2 | iron from a mountain foot within 6 |
| Tailor | 2x2 | 10 wood, 6 planks | 1 | leather into clothing |
| Trading post | 3x2 | 24 wood, 8 planks | | brings the merchant, stores 300 |
| Church | 2x3 | 20 wood, 10 planks, 24 stone | | +0.15 happiness within 16, the townhouse civic |
| Manor | 3x3 | 30 wood, 12 planks, 20 stone | | the lord's seat, 4 beds, claims land within 22 |
| Watchtower | 2x2 | 16 wood, 8 stone | | shoots raiders within 10, defence 6 |
| Village hall | 3x3 | 30 wood, 10 planks, 10 stone | 2 carters | founds a settlement, stores 150, claims within 16 |
| Brewery | 2x2 | 10 wood, 6 planks, 4 stone | 1 | grain and firewood into ale |
| Tavern | 2x3 | 18 wood, 8 planks, 4 stone | | +0.08 happiness within 12 while it has ale |
| Saltworks | 2x2 | 12 wood, 6 stone | 2 | salt, needs water beside it, all year |

## Town tiers

A cottage can be raised twice. Each tier holds more people, pays more tax and asks for more.

| Tier | Beds | Upgrade | Needs | Tax | Happiness |
| --- | --- | --- | --- | --- | --- |
| House | 4 | | | x1 | |
| Burgher house | 6 | 10 planks, 6 stone | a finished, stocked market within 14 tiles; ale, one per adult every 12 days | x2 | +0.05 met, -0.10 unmet |
| Townhouse | 6 | 12 planks, 16 stone | a church within 16 tiles; ale every 12 days and salt every 20 | x3 | +0.08 met, -0.15 unmet |

The upgrade button on a house says why it is refused: not finished, damaged, already at the top,
or not yet learned by your house. A house pays its ale and salt from its own shelf, so labourers
must keep restocking it; a townhouse that runs dry hurts more than a cottage ever helped.

Why bother: tax and standing. A townhouse pays three times a cottage and counts four points of
standing against two for a burgher house, and standing is what the rival houses are measured by
(see [Dynasty and chronicle](dynasty-and-chronicle.md)). The tavern only counts while it has ale
on the shelf.

## Settlements

Every building belongs to a settlement, the one whose seat is nearest. The first settlement grows
around the stockpile and later the manor. A **village hall** finished in a free region takes the
whole region and founds a second settlement around itself; it may not stand within 8 tiles of an
existing settlement centre. A **manor** takes a free region too but founds nothing.

A settlement is called a hamlet while no house is above the first tier, a village once some are,
and a town once half its households are burgher houses or better.

Work is hired inside the settlement first (see [Villagers](villagers.md#jobs)), so a hall raised
with houses beside it keeps its workers local. Anyone who works here but sleeps in another
settlement is counted on the settlement row as **commuters**; a growing number there means the
workplaces have outrun the beds, and the next house you build should go beside them.

Rival houses hold a walled seat of their own in every region they own - a hall inside a palisade
ring with one gate - which you cannot enter or build in until you break it; see
[Raids and defence](raids-and-defence.md#campaigns-on-the-map).
