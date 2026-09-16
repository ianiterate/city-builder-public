# Villagers

Every person in the village is simulated individually: where they live, what they carry, how
hungry and cold they are, and what they decide to do next.

## Needs

Two meters drive everything: **hunger** and **cold**.

- Hunger rises by one unit a day. One meal takes it back down by one.
- Cold rises with the season: almost none in spring, none in summer, a quarter unit a day in
  autumn and a full unit a day in winter, multiplied by the weather. A villager without clothing
  gets cold 1.5 times as fast. In spring and summer cold thaws by half a unit a day.
- Hunger reaches 1.0 about a day after the last meal. From there the villager is **starving** and
  their health drains away over five days.
- At 40 % health a starving or freezing villager **collapses**. They stop working, walk at 40 % of
  their speed, and want nothing but food or a lit hearth - they will not haul, build, sleep or
  stand a watch. The drain halves while they are down, so a collapse buys you time: death comes at
  zero health, about eight days after the last meal on normal difficulty.
- Cold is the same story, faster: at a full cold meter a villager is **freezing**, collapses after
  2.4 days and dies after 5.6.
- A villager who is neither starving nor freezing heals a quarter of their health a day, and gets
  back on their feet at 80 % health. A collapsed villager who reaches food eats their fill and
  carries a ration back to the fire, and heals twice as fast while lying still, so feeding them
  or lighting the hearth is enough.

Warmth comes from a lit hearth. Sleeping at home with the hearth lit removes two units of cold a
night; standing at a fire removes four a day. A hearth is lit only if the house has firewood on its
shelf: each house burns 0.2 logs a day in spring, none in summer, 0.4 in autumn and 1 in winter,
times the weather.

## What they do all day

A villager's brain checks, in this order: is there a raid, am I hungry, am I cold, is it night,
am I carrying something to deliver, do I have a job, is there labour to do, otherwise wander.
Children never work.

- They go to eat when hunger reaches 0.8, but if a larder is within 4 tiles they top up already
  at 0.5, and they eat straight from what they carry if they are starving. Long commutes used to
  starve workers; now a worker walking past food eats.
- They go to warm up at 0.5 cold, or already at 0.25 in autumn and winter when a hearth is close.
- They prefer their own house's larder and hearth over a public one up to 6 extra tiles away.
- At 90 % of the day they go home to sleep. Villagers are hidden while inside.
- Walking speed is 0.3 tiles a tick, 40 % faster on roads.

## Houses

| House | Beds | Upgrade cost | Requires |
| --- | --- | --- | --- |
| House | 4 | 16 wood to build | |
| Burgher house | 6 | 10 planks, 6 stone | a market in range, ale on the shelf |
| Townhouse | 6 | 12 planks, 16 stone | a church in range, ale and salt |

Houses are larders and woodpiles: each keeps a few days of food and firewood on its shelf and
labourers restock them from the stores. See [Buildings and town tiers](buildings-and-tiers.md).

## Population

- Villagers age four years for every game year. They become adults at 14, elders at 55, and die of
  old age between 55 and 80 with rising odds, certainly at 80.
- A housed couple aged 16 to 45 with a free bed and food on their shelf has a 3 % chance a day of a
  child, as long as their settlement holds at least 15 days of food per head.
- Every 30 days settlers may arrive: two adults, if there are at least two free beds, 20 days of
  food per villager and town happiness of 0.5 or better.
- A new game starts with 6 villagers aged 16 to 36 and a stockpile holding 60 wood, 120 grain,
  40 meat, 30 firewood, 12 tools and 12 clothing (scaled by difficulty).

### When the village is small

A settlement with fewer than **6 adults** rallies: everybody left moves 30 % faster and carries
30 % more, and they keep it up until the settlement is back to **10 adults**. A hamlet that has
just lost half its people can still walk the food home.

If a settlement falls under **4 adults**, word gets about and **desperate stragglers** turn up at
the door: three ragged travellers with two sacks of grain and a bundle of firewood, asking for a
roof. Taking them in is three pairs of hands; sending them away still leaves you the sacks. See
[Traits and events](traits-and-events.md).

## Jobs

Jobs are rebalanced once a day. Food jobs come first, then firewood, then everything else in the
order it was built; seasonal fields jump the queue in their season. About half the workforce at
most goes to food. What counts as short is the amount the village wants to **keep at least**: 20
days of food, 15 days of firewood per house, a tool and a set of clothes per adult, and a set
amount of each material (60 wood, 20 planks, 20 stone, 10 iron, 10 leather). The food and firewood
lines are measured against the highest population of the last 30 days, so a raid or a hard winter
does not quietly shrink the buffer the village works towards. A reserve of labourers is kept back
in every settlement for hauling and building: two or a third of the adults while anything is under
construction, one or a fifth otherwise, and none at all in a hamlet of fewer than three adults.
You can lock a villager to a job on the villagers screen and the daily rebalance leaves them
alone.

**Hiring is local.** A workplace takes people from its own settlement first, and from the home
nearest its door before one further off; a job in another settlement counts as thirty tiles
further away, which is what keeps a hut staffed from its own hamlet. Only when every idle pair of
hands in the whole realm is already busy does it reach into another settlement - and then the
worker does not commute for ever: they **move house**, taking a free bed in the workplace's
settlement and walking over with their pack on their back. If there is no free bed there they
commute instead, and the settlement panel counts them so you know to build houses. Building a hall
with a few houses beside it is what keeps a new settlement's work in local hands.

**Shifts last three days.** Once a villager is put on a post the daily rebalance leaves them there
for at least three days, so a good worker is not shuffled between a field and a quarry every
morning. The rule is suspended for food and firewood work while people are starving or freezing:
in an emergency every hand can be pulled onto bread and logs at once. While the realm is out of food or someone is starving, everyone in ordinary work goes back to labouring and foraging; only the militia, the carters and the people who make food stay at their posts. When a workplace needs someone
it prefers to take back the worker it had last, rather than a stranger who must learn the walk.

You can also decide yourself: on the villagers screen a household can be sent to another settlement
with **Move to**, and locked there. A locked home is never moved again by the governor, neither for
work nor when the lord takes over a house.

A worker with a **tool** works at full speed; without one at half speed. A tool lasts about 80 days
of work. **Clothing** lasts 360 days and halves the winter cold.

## Happiness

Every villager has a happiness value that drifts toward a target each day. The target starts at 0.5
and moves with:

| Condition | Effect |
| --- | --- |
| Housed | +0.10 |
| Homeless | -0.20 |
| Starving or freezing | -0.30 each |
| Clothed | +0.05 |
| Two or more kinds of food in store | +0.10 |
| Each tax level | -0.08 |
| Church in range | +0.15 |
| Market in range | +0.10 |
| Tavern in range, stocked with ale | +0.08 |
| Manor, hall, well, watchtower in range | +0.06, +0.05, +0.05, +0.03 |
| Burgher or townhouse needs met | +0.05 or +0.08 |
| Burgher or townhouse needs unmet | -0.10 or -0.15 |
| The lord's death | -0.20, fading over 30 days |

Below 0.4 a villager has a 15 % chance each day to refuse to work. Below 0.25 for 20 days in a row
an adult emigrates.

## Deaths

Villagers die of starvation, cold, old age, raiders and the occasional plague event. Every death is
written into the [Chronicle](dynasty-and-chronicle.md), and the steward raises an alert while it can
still be prevented (see [Alerts](alerts.md)).
