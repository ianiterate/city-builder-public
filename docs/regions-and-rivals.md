# Regions and rivals

From the fifth chapter on, the game is a contest for the valley between your house and two rival
houses that grow, settle, covet and march on their own.

## Regions

The valley is cut into 6 to 14 regions of roughly 350 land tiles each, named like Ravendale or
Thornmere. Your start is always region one. A region has one owner or none; on the ground a border is a
faint line in the owner's colour with a marker post every few tiles, not a fence. Press M for the regional map: hover a region for its holder
and the claim meters, click it for what stands there, your claim broken into its parts, and what you
may do about it.

## The two houses

| | Hill Folk | Marsh Men |
| --- | --- | --- |
| Start attitude to you | +0.2 | -0.3 |
| Temperament | cautious | warlike |
| Start population / army | 14 / 3 | 18 / 5 |
| Share of people under arms | 15 % | 30 % |

Each house lives on the same ledger as you. Every day it feeds its people, grows toward the
capacity of its land, earns half a gold per head a season and pays a gold per spear, and drifts its
army toward its target. Every ten days it decides what to pursue: grow, settle free land, covet a
neighbour's region, recover lost land, or defend. It expands once its population passes 70 % of
capacity and marches only when its claim is over the line, it can pay, and it reckons itself 1.1
times stronger than the defender, four times against a capital. Houses also deal with each other:
they sign pacts, quarrel and fight off the map. A house far behind the leader grows faster and the
leader slower, until the valley is won.

A house remembers. A refused demand, a campaign against it, or a region taken raises its grudge;
gifts, pacts and marriages lower it. Grudges fade with a half-life of about half a year, and
attitude walks slowly back toward the house's nature.

## Claims

Every house carries a claim on every region, updated daily. Yours on a region grows from:

| Source | Per day |
| --- | --- |
| each owned region bordering it (up to 3) | 0.15 |
| each finished building of yours inside it (up to 10) | 0.15 |
| a finished hall or manor inside it | 1.0 |
| your standing, on bordering regions | standing / 1000 |
| being at war with its owner | 0.3 |
| a marriage with a house | +15 once, on regions bordering theirs |
| a gift to a house | +2 once, on the same |

A claim nobody feeds decays by 0.05 a day. The owner of a region holds it at 100, rising slowly
with tenure to 150. Roads add nothing.

- A **free** region falls to the first claim over **60**. A house must also have 8 people per
  region it would then hold, or the land stays empty.
- Someone else's region can be demanded or marched on at **40**; a capital, the region a house's
  first seat stands in, needs **70**.
- When a region changes hands every other claim on it is knocked back to a quarter.

The quick way to take free land is a **village hall**: finished in a free region it takes the whole
region at once and founds a second settlement. A manor does the same without founding anything.

Gains and losses are announced with their reason (founded, settled, claimed, ceded, conquered,
absorbed) and written to the chronicle. Losing a region loses the buildings in it; winning it back
restores them at half health. Losing your capital region ends the house.

## Demands

An envoy may arrive with a demand: **cede** a region, or pay **tribute** (only from a warlike,
hostile house much stronger than your capital, at most every 180 days). You have five days to
answer; silence is a refusal.

- Cede: the region passes, the house warms and a 180-day truce follows.
- Pay: the price is 40 gold plus 0.15 per tile of the region (tribute: 30 plus a third of your
  standing); their claim on it drops to zero and a truce follows.
- Refuse a cede: war, and a band takes the road with six days' warning. Buying it off on the road
  costs one and a half times the price. Refuse a tribute: a stronger raid instead.

## Campaigns

You can march on a region you border once your claim is over the line and at least four militia
are ready. The campaign button lists what is missing as a checklist: border it from more regions,
build in it, raise standing, assign men, wait out a truce, or renounce a pact first. The estimate
shows both strengths and a low and high count of the dead before you commit.

The fight itself happens on the map: the band musters at a border post, crosses, and has four days
to break the ring around the rival's seat and burn the hall. The garrison sallies out to stop it.
See [Campaigns on the map](raids-and-defence.md#campaigns-on-the-map) for the hit points, the
torches and the casualty rules. A won conquest takes the region, 15 standing and 20 gold plus a
fifth of the loser's wealth, and ends the war with a 180-day truce.

A **raid** on a house's home region needs neither claim nor border and takes no land; the band
loots and leaves.

Houses campaign against you the same way, on your ground. "Walls that held" is the card for
repelling one.

## Diplomacy

On a house's screen:

| Act | Cost | Needs | Effect |
| --- | --- | --- | --- |
| Gift | 20 gold (60 at war) | 20-day cooldown | +0.1 attitude, +2 claim on bordering regions; at war it buys peace if they are not too bitter |
| Trade pact | 50 gold | attitude 0.3 | 120 days: the merchant comes twice as often, +5 % standing; breaks if attitude turns negative |
| Marriage | | attitude 0.5 and a free adult heir | attitude to at least 0.8, their growth halved, +15 standing, +15 claim on bordering regions |
| Raid them | | attitude below 0 | a loot raid on their home region |
| Take them under your banner | | attitude 0.5 and their standing under a third of yours (a quarter after a won raid) | every region they hold becomes yours, +25 standing |
| Renounce pact | | a pact | ends it the same day so a campaign can march; -0.2 attitude, +0.25 grudge |

Each button says its price and, when greyed, why.

## Winning the valley

Holding 60 % of the regions (or every house's home region) while your standing is above every
remaining house, for 120 days in a row, makes you Lord of the Valley. See [Endgame](endgame.md).
