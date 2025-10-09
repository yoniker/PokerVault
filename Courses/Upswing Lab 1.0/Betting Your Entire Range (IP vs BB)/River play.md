My summary: Need to think about the core of ranges both in the bet-check line and bet-bet line.
After checking back turn, oop player will have top pair advantage, which can go for B75. Always think about what's the core of the value ranges, how the ranges interact, if draws completed we can bluff our future bluffs hands etc

# River Play Strategy - Transcript Notes

## Core Concepts

### Range Construction After Bet-Check

"Usually in position bets most of their best hands, so the crux of the checking ranges, weaker top pairs, our showdown value, which is usually any pair that's not a value bet, and then some ace highs. We'll have some draws because we always mix these and we have a decent amount of air."

"Out of position on the other hand is usually quite a lot more paired than us. They also have a bit of a nut advantage here. That's because after they call flop they do raise their nuts there. They usually improve to some hands on the turn and then again to some hands on the river. Whereas in position the nuts only really come from hands which improve on the river. So there's usually a little bit of a nut advantage for out of position. They're also very paired so they have a bit of a linear advantage. The third point is they have less air and that's because they have to check call the flop bet."

### Block Betting Strategy

"In general, out of position will kind leverage their nut advantage to build a block bet strategy and a big bet strategy. The block bets are based around hands, I like to think of it as they're worth a little bit more rather than checking, but they aren't beating hands which in position reopens for value. I kind of think of it as your block betting to save a bit of money versus the hands which bet, check bet, and can't raise you but you also make a bit of money versus the weakest showdown value hands, which would just check down if you check."

"We like to protect this range with some of our nutted hands and we usually try, I call it card matching. This will be easiest to show in the examples, but you like blocking the traps that share cards with your main block bets. For example, if you are block-betting your eight x on the river, you'll try to block bet with two pair hands, which include the eight. That just makes it harder to kind of bluff your range efficiently."

### Big Bet Strategy

"The big bet strategy is usually leveraging out of positions advantage in top pair hands. This isn't always the case, but usually, if the top pair remains unchanged, out of position will have an advantage in top pair. These hands usually form a big bet strategy. This is usually less protected than the small bet and that's just taking advantage of the fact that in position usually doesn't have too many nutted hands."

### Checking Range for Out of Position

"Then we think about the checking range for out of position. This is based around showdown value, so hands which aren't quite good enough to block bet, and the solver likes to check-raise quite aggressively to help get these hands to showdown."

### Facing Bets In Position

"So facing a bet, we're allowed to slightly overfold. This is because in order for out of position to bluff here, they have to have floated a somewhat weak hand on the turn. This weak hand also has to fade a turn barrel in order to get the chance to bluff on the river. So the solver likes to try and make these sorts of defends zero ev on the flop so they're allowed to profitably bluff river, but in order to get to the river they have to call the flop and fade a turn barrel. Usually, we see these spots are slightly overfolded versus all the bet sizes."

"Versus a block bet in position wants to raise pretty much any hand which beats the hand, which the blocks are based around. That's a bit of a tongue twister."

## Hand Examples

### Example 1: Tc 8d 2s Board

"I'll take up an example to show it. I'll go with a ten eight two, we'll go with a brick turn. So we overbet most our best top here, but we do have some. Check check and I'll go with a pretty bricky river too."

- **Turn (4d):** Check-check
- **River (5h):** "Here we see all three sizes being used a bit, but I'm focusing on the block bet here. So the block bet in this spot is based around, it's actually weaker eight x and under pairs."

"If we go back to our rules, we say the block bet is based around hands which are worth a little more, but they are beat by the bet check bet. Here if we look at the bet check bet the value threshold is kind of any eight. So we see the hands that are beat by the bet check bet hands like pocket sevens and pocket sixes. These like squeezing a little bit of value versus hands like ace high which call really often, but they save money against hands like these eight x which are betting."

#### Facing the Block Bet

"We're talking about facing the block bet in position. You have to bluff catch really wide. We get to raise any hand which beats these main block bets. So in this case it's a good eight or any ten and we see that here, it's demonstrated pretty clearly."

#### Facing the Medium Bet

"This is the big bet. We again raise any hand that the bets based around so back to the example. I'll look at the medium bet for now. So the medium bets a strong eight or a weak ten. These weak tens are just all over betting. It's literally a strong eight here. Given that we raise most of our ten x and then any two pair hands."

"It's also a bluff-catching spot so the removal is very relevant. In this case, we need to think about what the bluff hands are on the river. If we click on this, we kind of look for the air hands in the range and that's generally going to be the straight draws here."

"We look at the out of position strategy on the river. The threshold for bluffing is kind of anything worse than king queen by the looks. A lot of the bluffs are going to involve cards like a nine, jack, or queen. We won't want to bluff catch with them because we are trying to unblock the bluffs."

"If we see the bet, it's a medium size and it's a good eight or better. We have to call anything which beats that. So yeah, we see all these eights are calling because they kind of are too good essentially. Then when we get to the bluff catcher hands, it's going to be mostly ace highs here. So we see that ace six is calling a lot, ace sevens calling a lot, but then ace nine, ace jack, and ace queen are folding. That's because these block the main bluffs from out of position."

#### Facing a Check

"Facing a check, we're usually at a bit of a nut disadvantage. This means we tend to reopen small. I tend to run my sims with just half-pot sizing and then a big sizing in case we pick up nuts. In this case, I've left in a 70% size, but we see here it doesn't get used very often and the 50% is the preferred size."

"We talked about it earlier, but the threshold for this is any eight or better, which looks pretty thin if we consider how often the value hands for out of position are betting, the checking range is more ace high heavy."

### Adjusting to Opponents

"It's worth noting here that this is potentially not how your opponents will play. A lot of people will bet a lot more polar on the river. When that's the case, I think you want to reopen more polar as well."

"I'm actually just going to run a sim on that because I want to double-check. I'm running a sub-tree for this. I'm just going to let out of position overbet and this will reflect a more polar betting range. If we think our opponents playing more like this, so they're just checking and it's like a jack eight, nine eight, which I think is actually a pretty reasonable assumption versus a lot of players. We see that the threshold for reopening goes up quite a lot and we prefer bigger sizes given that we're reopening more polarized."

"Yeah, I think you need to pay attention to your opponents. I can't talk about pool frequencies, I only know the pool I play in and it is a relevant factor in my pool. I haven't actually adjusted as much I maybe should though. I think that's actually a really nice demonstration of how we should respond to people who are betting in the river to polarized."

### Example 2: Qs Ts 3d Board - Triple Barreling

"I'll go to a queen ten x example, brick turn and we'll look at the river, for example, an eight."

- **Turn (5h):** "We want the barrel though."
- **River (8h):** "Here's a good example of how complex the solvers play. We see that the nutted hands here are playing all three sizes to help protect the weaker value bets."

"For example, here, kings still want to barrel, but you don't want to just bet pocket kings because that allows your opponent to jam anything better for value. So to counteract that we see some of pocket tens, for example, some jack nine, which is a straight, betting the sizes to help protect those hands."

"In practice this is really hard to implement, finding all these shreds and a nice kind of exploit versus most players who won't bluff raise is just bet what you think your hands worth. If they're not raise bluffing. They literally cannot punish this as long as you bluff the sizings too."

"A decent approach here is to shove your sets, for example, because they're worth all of the money. You can bet 150% with these over pairs and then smaller with the queen highs. This really exploits opponents who won't bluff raise."

#### Bluff Raising Example

"Just to show you an example of how the bluff raise should look. If we bet the 70 size here, this is a protected range, think about it. In positions shoving with hands like queen eight. So all these two pair hands, which are actually quite thin, if you think about how many straights are in the in position range and better, two pairs."

"The solver is playing quite fluid based on the sizing and how thin it goes for value. We look at, for example, one 30, it's still shoving some of these weaker two pairs. Solver is really punishing these smaller bets with both kind of thinnish value raises with hands like ten five, but also pretty sick bluffs from stuff like jack ten, queen nine, queen jack."

"If we think our opponents aren't finding these bluffs, we can be more exploitative with our barrel compositions."

## Key Takeaways

### Triple Barreling Philosophy

"Finally, I want to talk a little bit about tripling. It's really hard to come up with general rules in the triple barrel and that's because it's so dependent on the runout and there are too many combinations of turn and river to give general rules."

"I will say that an important thing to consider with bluffing is you want to think about how many of your bluffs improve. For example, the river completes all the flushes, so it's a flush completer and a straight completer for example, you gonna need to be a little bit creative with your bluffs. All those future bluffs you barreled. I hope you do, need to be bluffing rivers. On the other hand, if the river completes none of the draws and misses your future bluffs too, you need to be really careful with bluffing."

### Sizing Considerations

"In addition, sizings on the river are a bit complicated too. The solver really likes protecting bet sizings just because the way the solver works is it always knows the strategy its opponent is playing. So it needs to not be vulnerable in any line. Human play, we don't know the strategy the other play is playing so you can be a little bit more vulnerable."

"Thanks for watching and I'll be back with some practical examples."