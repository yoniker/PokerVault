My summary:
Different lines (such as x-x-x-x vs X-B30-C-X-B150-C-X-B75) will yield different core ranges for the IP player for example when he is the PFR, for example, KT+ as the core range, or mostly a-highs with some weaker board pairs in the passive line.
I should view the different ranges in the solver, and can write it down, like so:

X-X:
Lot of weaker pairs weaker than K9

88-QQ,33,22
7x
4x
Some Ahigh/air
and so:
Kx worth an overbet
Jx 75%
88-99 30%

after turn checks again (where kx and strong Jx mostly bet), core of range is:
-Ahigh
-weaker Jx
-Air
-TT-88,4x,55/66/22/33



# Working Out Hand Values - Coaching Transcript

## Core Concepts

### Ranging Process and Hand Values

"Hey guys, welcome to this video. I'm working out how much our hands are worth. The general idea here is that we kind of range each player going back and forth and based on how each other's range looks, it kind of determines how thin or wide we can go for value."

"So the general process we want to go through is what is the core of the range we are facing and then how much is the core of our range versus this."

## Hand Examples

### Main Example: BB vs BTN Single Raised Pot

* **Board:** Ks7h4s
* **Turn:** Jd  
* **River:** 2c

#### Triple Barrel Line Analysis

"On the King Seven Four board we kind of expect our opponent to bet pretty high frequency for a small size on the flop, so that doesn't change their range too much. On the turn Jack, we expect them to play a polarized strategy betting like a good King and better for the most part. Facing that polarized strategy on the turn, we'll call all of our top pairs and we'll call some second pairs as well."


"In the triple barrel line, say, there you go, bet thirty flop, bet one fifty turn and bet seventy on the river. What hands do they have that makes sense in this line? Well, what is the core of the range they're facing? My range is mostly King x with some weaker pairs. That means that facing a river bet I'll have to call a lot of top pairs and I have some two pairs."

"So the hands that are good enough to go for this line, it's going to be a good top pair or better. It's going to be something like King Ten plus for this sizing on the river just because it's such a bricky runout."

"Now, if in position is betting something like King Ten plus, that means for out of position, King Nine and lower is worth around about zero. So if in position can bet roughly King Ten plus for the sizing, as the out of position player, our King Nine then works as bluff catchers. This means they're worth about zero chips. Some will be profitable calls based on their blockers, but for the most part we just have bluff catchers which are worth zero."

#### Solver Analysis - Triple Barrel

"So for the solver I've got big blind versus button King Seven Four suited on the flop. We see in position is betting most of their range, slightly weighted down with the standard hands like the showdown value hands and the good over cards that don't have many nice properties for betting."

"When they c-bet flop and call, and we get the Jack of diamonds turn, we see in position is playing an overbet or check strategy on the turn. I have rounded the strategy slightly so there's no small betting, but yeah, this is what most players are playing. And we see here that they can bet kind of good top pair or better on the turn. This is sort of what we assumed."

"Now, from the in position perspective, they need to work out roughly how our range looks so they know how often they can go on the river. And we see here that we're calling all of our top pairs. We're calling a lot of our second pairs and we're calling some of our even weaker pairs, although these mostly have a flush draw."

"So once we call, we see the river range for out of position is displayed by these bars here and forty-seven percent of our range is top pair, only seven percent is two pair and then the rest of the range is made up by lower pairs or draws."

"So we get the very bricky two of diamonds. This really doesn't change the ranges much. We don't make many two pairs, so our range is still mostly just top pairs and second pairs. This means facing a seventy-five percent bet. We're going to have to call pretty wide."

"Given we have to call most of our top pairs on the river, a good top pair or better is good enough and we do see that the line is King Ten. So facing this bet, we want to think about how much our hands are worth and we see here that when the solver is mixing, these hands are worth zero, because they can call or fold. So facing this really strong looking line, we have some really strong hands that get made indifferent here."

#### River Shove Analysis

"Now this is going to be even more extreme if they go for the shove on the river. Facing the shove, we'll still have to call two hundred and forty to win three hundred and forty, which means if they're bluffing it needs to work seventy percent of the time. That means as the out of position player we now call roughly thirty percent of the time to make their bluffs indifferent."

"What this means is we'll call our top ten percent of two pairs and then we'll call another twenty percent of the range and top pairs. So given we still need to call lots and lots of top pairs, they can shove as wide as Ace King for value and that's what we see in the solver here. Facing the shove, we indeed do see that all the two pairs are calling and we still have to call lots of top pairs."

"When we're thinking about how much hands are worth though, if the value range is mostly Ace King and better, that means that any hand worse than Ace King is going to be worth around zero."

#### Check Back Turn Line

"Now how does that change if they decide to check back on the turn? Now, first we need to give the in position player a range and it's essentially their opening range minus the hands which they bet on the turn. That means the core of the range is King x, although a lot of them are barreling turn. There's lots of Jack x, there's lots of pocket pairs and there's lots of low pairs, as well as a decent amount of Ace highs and some air."

"So we can simplify that range to having a core of pairs weaker than King Nine and then some Ace highs and air. The core of the range though is King Nine and worse and for the most part it's going to be Jack x and pocket pairs."

"What this means from the out of position perspective is that a hand like any King now is going to be worth so much money because most of in position's Kings bet on the turn and the Two really doesn't change on the river."

"So if we go to this line in the solver and we make the solver check back turn and the Two of hearts river, we see that our King x are all worth one point five times pot. So our King x here are worth so much money. That's because when we narrow down the ranges, most of the ranges are just Jack x and pocket pairs, which means they have to call lots of them versus our river bet and our Kings are just worth a lot of money."

"We also see that our Jack x that get here, we don't have many, but when we do have them they're worth a big bet too. I think a mistake a lot of people make is undervaluing how much a hand like second pair is worth here. You need to remember that in positions can bet most of their good hands on the turn. So when we get such a bricky river, these hands are just worth a lot of money."

#### Check-Check-Check Line

"Now we'll see this even more extreme in the check down line. So again, we need to go through the same ranging exercise. To summarize the bet check line, on this runout on the river, King x was worth an overbet, Jack x was worth seventy-five percent pot and pocket Eights and pocket Nines are worth a thirty percent bet. This made a lot of sense when we thought about the ranges."

"Next I want to jump into what happens when it goes check check on the flop, check check on the turn and then we're in the river spot as out of position. Again, we are going to be ranging our opponents and we can immediately give the opponent's range a core on the flop once they check back, because it does narrow the range a lot."

"The main hands that sort of check back on the flop, again, would be weak Kings, pocket Queens through pocket Eights, pocket Sixes, pocket Fives, pocket Threes and Twos of course, and then some of the weaker board pairs as well, as well as a lot of Ace high. Ace high is worth something at showdown if it manages to check down all the way. So we'll see the solver trying to maneuver especially hands like Ace Nine and Ace Eight to showdown."

"So we can immediately write the range after the flop check like this. And then there's some weak Kings as well, which are a pretty important part of the range to limit how much out of position can put in."

"At the moment the range is still pretty diverse, but it'll get narrowed again on the turn when it goes check check again. On the turn we expect them to delay c-bet a lot of their remaining King x and hands like Queens or Ace Jack, like a good Jack, can start betting on the turn as well. Even if they're betting like a fairly large sizing, like seventy-five percent pot."

"What this means is we need to narrow the range again, I think we can even start calling King x as a supplementary hand at this point once they check back the turn because it's really there to support these hands getting to showdown more than wanting to take that line."

"So I think the core of the range, after the turn check, looks more like a lot of weaker Jack x, which improved on the turn. Then lots of the pocket pairs below a Jack, lots of Seven x, Four x, underpairs and Ace highs."

"On the Two river, which doesn't really change much, we need to start thinking about how much our hands are worth as the out of position player facing a range like this. When we think that the core of the range is mostly capped out at a Jack, that probably means we can bet any Jack for a medium size, something like seventy percent pot. King x is clearly worth an overbet and a good King can probably even start check-raising on the river and try to build a really big pot."

"As the weaker hands, any Jack can clearly bet a medium size, but even hands as weak as like a Seven now want to be block betting. When we look at the range, there's a lot of these pairs weaker than a Seven as well as a lot of Ace highs. Ace highs make up a significant portion of the check range. So block betting really thin in these lines is quite important."

#### Solver Analysis - Check-Check Line

"At this point I want to jump into the solver and we'll be able to see these ideas more clearly. So on the flop we want to look at the core of the check back range, and again, it's a pretty consistent pattern. The hands which are really trying to work its way to showdown, there's lots of Ace highs, lots of the weaker Sevens, the weaker Fours, and then a few King x to help support our hands get to showdown."

"Now on the Jack turn out of position probes polarized and in position starts to bet most of their King x on the turn. I really like this graphic on the right, which shows how our range is broken down, and we already see on the turn like thirty percent of our range is Ace high, decent amount of air as well. And then lots of these low pairs, second pairs, third pairs. So this chunk of the range is really the core of the range that we're talking about."

"Now, once they check back, our range in position shifts even heavier towards these hands. We see that hands weaker than a Jack make up eighty percent of the range. That clearly should show that a hand like a Jack is going to be worth a lot here."

"Looking at the strategy, we see hands like our good Kings actually getting used to support other rangers. We're looking to check-raise these hands versus a bet for a massive sizing. So we really want to pile in the money here with a good King. We're seeing our weak Kings going for the big overbet and we're even seeing some of our strongest Jacks overbetting here on the river."

"So Jack x is just worth a lot here. We see our middling Jacks betting seventy-five percent and any of our Jacks can bet for a small size. We see hands as weak as pocket Fives block betting here."

"I was thinking Seven x would block bet, but pocket Fives is just really nice and it makes sense when we look at the solver. There's so much Ace high in this in position range that you really want to be block betting against. You also have to remember when you're making these really small bets, the in position player cannot fold very often whatsoever. So when they block bet, and we look back at this graphic on the bottom right, we see the Ace highs calling more often than not. They're calling all pairs they have. So this kind of explains why we can block bet so thin."

## Key Takeaways

### Hand Values Summary Across Different Lines

"Here are the different lines we looked at and how much the different hands were worth. We saw facing the triple barrel for the small size on the river, King Nine and worse was worth zero. And if they shoved river, even King Queen was worth zero."

"Now, the amount of hands' worth changes so much based on the line we're facing. We saw if instead of facing a triple, if our opponent checked on the turn, our King x wanted to overbet themselves and even a hand like second pair Jack x, wanted to bet for a big size as the out position player. Even our pocket Eights and pocket Nines wanted to put in a small bet on the river."

"Now this got even more extreme if we looked at lines where the in position player checked back the flop. With the checked back flop and checked back turn on the same board texture, our hands like King Nine, which were indifferent in this first line we looked at, we're actually looking to check-raise for a big sizing on the river."

"So given the in position player had narrowed their range by checking twice and removed most of the good hands, a hand like a top pair King is looking to check-raise and build a massive pot. We also saw hands as weak as second pair overbetting and hands as weak as pocket Fives, which looks so weak on this board with three overcards to it, are still block betting, even though a lot of the in position range is pocket Tens, Nines and Eights."

"When they check twice so much of the ranges is Ace high that we do just want to be block betting and we get value like that."

### Final Thoughts

"So it is really important to be very conscious of how the ranges look and based on the line you're facing, your hands are worth very different amounts of money. It's a very, very common mistake for newer players to undervalue how much hands are worth, especially in a line like this bet thirty and check back turn. You often see even decent professionals betting too small with their King x and their Jack x."

"So practicing things like this, narrowing down the ranges throughout the hand and just getting in the reps really in a solver like Lucid or like Pio to just get a good feeling for how much hands are worth in different lines is really important, in my opinion. And I hope this was a good insight to that. Cheers."