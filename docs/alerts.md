# Alerts

The steward watches the realm and raises a card when something is about to go wrong. An alert has
a severity (warning or danger), a cause, a suggested fix, and a button to jump to the place. You
can mute a kind for seven days.

An alert only fires after its condition has held for half a day, and it clears only when the value
has recovered to one and a half times the line, so it does not flicker.

| Alert | When |
| --- | --- |
| Firewood low / out | the realm has 6 / 2 days of burning left |
| Food low / out | the realm has 6 / 2 days of meals left |
| Freezing | someone has lost 35 % of their health to cold; danger at 70 % or three people, and always danger once anyone has collapsed |
| Starving | the same lines for hunger |
| Nobody splitting firewood | autumn or winter, under 12 days of firewood, no wood splitter working |
| Nobody making food | under 15 days of food and no food job working |
| Homeless | adults without a bed within 15 days of winter |
| Building starves the hearths | construction is eating the wood the hearths need |
| Local larder / local woodpile | one settlement has under 2 days of its own food or firewood while the realm has plenty |
| Walled in | walls leave villagers with no path to a storehouse that holds food |
| Stores overflowing | a settlement has had goods lying outside its stores for three days |
| No room in any store | a good being produced has nowhere left to go, and the workers have downed tools |

The two store warnings follow from how storage works (see [Economy](economy.md)): a full store
keeps taking goods as an unsheltered pile of half again its size, where food rots and timber
weathers, and producers stop only when that pile is full too, or when the realm is already sitting
on six times what it keeps at least of that good. The first warning names the settlement and asks
for another barn, granary or stockpile; the second means work has already halted somewhere.

**Starving and Freezing count the collapsed.** Once a villager's health falls under 40 % they go
down where they stand, and the alert says how many have collapsed and goes straight to danger, with
the jump button taking you to one of them first. Those people cannot walk far and cannot work: the
food or the firewood has to come to them. The fix line points at the nearest store, and at strict
rationing on the treasury panel if the larders are simply too thin (see [Economy](economy.md) and
[Villagers](villagers.md)).

Stock alerts are measured realm wide. In autumn the woodpile is measured against the winter ahead,
not the current burn rate, so a warning in late autumn means the winter stock is short.

Raids and campaigns arrive as their own banners, described in [Raids and defence](raids-and-defence.md)
and [Regions and rivals](regions-and-rivals.md).
