
My summary: When doing a deep dive, he tries to guess the overall strategy of a said turn card, and then tries to guess specific hand classes before filtering. Then he tries to give reasons, why this hand class does what it does. Looks at specific sub-groups of this hand class (for example, flush draws with a K and fds without a K) and again tries to explain why he thinks the solver does it. Finally, he nodelocks what humans will do, for example if he thinks that in-position humans will not bluff complete airball then he nodelocks it, and then looks at what changes.

He tries to learn new concepts as he looks at the sim.

# Turn Barreling Strategy - K♣7♦2♠ Rainbow

## Core Concepts

### Board Texture Differences

"Hey everyone. In this video, I'm going to look at king seven two rainbow. The big difference between this board and the previous board we looked at the queen ten two is that this board is much more disconnected."

### Flop Action and Ranges

"So again, we're looking at a range bet, so out of position, checks range and in position bets, their entire opening range. We can see immediately that the out of position player has to continue with much weaker hands than they did in the queen ten two example. This is because there are less pairs in the range."

"When there's two broadway cards this section of the range here interacts a lot better with the board, meaning that on average both players hit more middle pair but also two pair hands and straight draws. On the king seven two where there's no flopped straight draws, the kind of hand strengths all shift down."

"Ace high is now a better hand and we even see some quite weak two unders hands just check calling. Ten nine for example, here is just a backdoor straight draw but the solver likes continuing it more than half the time. Its only nine eight and even has like six five with just a bare backdoor straight draw continuing."

"It seems a little strange on the surface but we have to consider that when both ranges have a lot of air on the flop, in position has a lot of air too. Most of this range is also unpaired so floats have a bit more immediate equity but they also have better prospects to float the flop and bluff later streets."

### Out of Position Calling Range

"When we're considering how this calling range looks, this has a lot of ace highs, a lot of the top pairs, most of the second pairs, and most of the bottom pairs as well as these pocket pair hands. Then there's a lot more air floating the flop just like two undercard hands, even some really weak backdoor flush draw, backdoor straight draw hands, like five three."

"In practice, I think a lot of people will miss some of these weaker floats, particularly these two undercard floats and some of the stuff like ten nine."

## Turn Categories

### Overview

"Here we are, we've got our king seven two, and again we are just going to think about, so given the range we described, how the turns look. I think on this board there are again four kinds of main turns. We've got the ace, high brick, and we have a low brick and as always we've got a pairing turn as well."

## Low Bricks (3, 4, 5, 6, 8)

### Strategic Framework

"Now the reason I'm distinguishing the bricks on this texture is because there's a pretty significant difference between the queen, jack, ten, and nine as compared to these lower eight, six, five, four, and three. These low bricks interact a lot less with the air in both ranges."

"This offset region will miss again on the turn, so that has a few impacts. It means that there are overall a lot less pairs in the ranges."

"Both ranges have lots of air. I think they'll generally be low equity for imposition and the final thing to consider is that given that all of these just two high card hands, a hand like second pair, so sevens and then hands like pocket eights, nines, and if we have the eight any eight x."

"What I'm saying is any kind of middle pair hand strength has quite a bit of incentive to bet to get the folds from these hands, even get calls from some ace highs and some lower pairs and then we still have the nut advantages in position. I think just given the incentive to bet middle pairs, I think a small barrel makes sense on these low bricks."

### Sizing Considerations

"I'll have a look at one of those turns first and we'll take the four of diamonds. We see the solver playing a two size strategy. This reflects both the fact that these seven x and pocket pairs really like betting and also that we have a nut advantage in particular king queen and aces like betting."

"In game I would probably just stick with the 70 barrel."

"This is really why we zoom in on what hands want to be betting and build our strategy around them. A lot of coaches will tend to recommend just any brick play over bet or check and that's totally fine too. I prefer to go with a more intuitive style. It makes us think a bit more about how the ranges are looking and the composition of them."

### Value Range on Low Bricks

"Starting at the top range, sets again, we've still got a pretty big nut advantage here and our range improves pretty well on rivers. We do see a tiny bit of trapping here. I think this is because the imposition range just has so much air now that it can be somewhat reasonable to have some traps."

"We see a cool perk of bringing some of our nutted hands into the smaller bet range is that we get to barrel more with these seven x hands. When we were playing the overbet too, our range overall got weaker so we couldn't be quite as wide like queen seven was betting a lot less and then these hands were never betting."

### Check-Back Strategy

"I think Ace King is actually a really nice check too. We block a lot of the hands which we'll call two big bets in king x and also we really don't need protection. So much of the outer position range is ace high. We're really happy to just let that stay in."

"If we get the ace on the river, we'll make a lot of money versus all those ace highs that would just fold turn. Additionally by blocking the ace, the frequency at which all those weak floats are in the range goes up and that means we face more bluffs on the river on average making Ace King a really nice hand to check back and it'll get bluffed into more often given your removal."

### Middle Pairs and Protection

"We then get to the weaker hands. I've talked about this briefly, but these hands really like getting protection from all those high card hands which have six outs versus them. These also will get significant value from any seven x, four x, and two x."

### Bluffing with Air on Low Bricks

"Here's where we see a little spice from the solver. The solver really likes barreling these two undercards which fold out dominating undercards, this sounds strange but when they bet and get called they have equity to pick up a pair which beats all these bottom pair hands which are always calling to."

"By betting on the turn with this region of hands we kind of clean our pair outs against the undercards which are folding from out of position. I think it's a quite interesting way to construct a barrel range and I don't tend to see this very often."

"I think more people would tend to barrel lots of ace high hands just thinking it's kind of a top pair draw. I think it's quite interesting that the solver chooses the style of barrel and it is due to the high number of air in both ranges. The ace highs are simply too good to be bluffing at a high frequency."

## High Bricks (9, T, J, Q)

### Strategic Differences

"Now we can talk a bit about high bricks and these are going to play more similarly to the queen ten x board. It's another Broadway texture, so nine two queen, the nine two queen brings extra second pairs to both players which has a few effects."

"First, it means that the ranges are both more paired, which means ace highs are now worth a bit less. Also, it brings a bunch of gut shots to both ranges, both of these lean towards top pairs betting a bit more often I think."

"Yeah, overbet strategy just makes sense on these turns and that's what we see."

### Value Betting Range

"So here we see is weak as king eight essentially pure barreling. This is even wider than we saw on the queen ten x board and that's a result of in position having more ten x than out of position."

"On the flop out of positions folding some of their hands like ten nine, ten eight, and these lower ten x whereas if the ten comes on the flop rather than the turn, these would all continue. In position has a bit of an advantage in the ten x there are fewer hands which out of position can value bet thin with."

"We don't need to protect our range with as many good top pairs, which is why we see the top pairs barreling so wide here."

### Future Bluffs on High Bricks

"Finally, we need to look at our no draw hands again and we're back to the more common pattern of future bluffs. We again see future bluffs for the straights, which include the jack, some for the queen, some for the ace."

"These have the added benefit of folding out the dominating ace highs as well as having, so that's why we see ace high barreling a lot here and then we see these total air balls which often pop up at low frequencies and then we have our future bluffs with the one diamond hand in this case often barreling."

## Ace Turn

### Range Dynamics

"The ace turn, now this is where we see a pretty big difference and it ties back to the flop strategy. On the queen ten, I think it was a queen ten three, ace is a really great turn for in position and that's because a lot of the ace highs from out of position were folding versus the small bet on the flop."

"In this case, ace highs were worth more because of how disconnected the board was. We see most of them calling the flop. I expect this to be a much less good card in this case."

"Lower equity and double Broadway and now I'm just thinking about what sizing makes sense. We need to consider if there's weaker hands, which makes sense a bit and king x really doesn't. There's not much merge betting and we've got a low equity board, so I think overbet or check makes sense."

### Trapping with Aces

"We see sets and we will see trapping with aces specifically. For aces here, it just blocks the main hands you're looking to get multiple streets of value against, doesn't need protection so it makes sense to trap."

"The big difference here is that a lot of the second pairs get to fold versus our bet on the turn just given how much ace x is in the out of position range. That's why it really sucks to block two aces here, given that even second pairs often get to fold."

### Polarized Strategy on Ace Turn

"Top pair, in this case we're going quite polarized. The ace x is a nice addition to the checking range, so our weaker pairs get to showdown more often. By checking lots of ace x out of position can't put nearly as much money in with their king x."

"Yeah, by checking back a lot of these ace x it really limits how much money out of positions king x can look to get in against our weak pairs."

### Flush Draws on Ace Turn

"If our range, king seven two rainbow ace flush draw, king x suited checks, and makes up a lot of flush draws, this allows us, which I notate with this arrow, this allows us to barrel more unpaired flush draws. Yeah, I hadn't really thought of this concept before but it makes a ton of sense. If there's a lot of flush draws which make natural checks in the ranges, you just get to barrel your unpaired flush draws a lot more."

### Gangster Bluffs

"Now no draw, I think that we'll barrel some of these gangster bluffs. Okay, yeah, so we do find these and that's again because just most of the range we talked about betting already was pretty equity driven. The solver really just likes adding some polarity to the ranges with these total air balls."

"Yeah, again, you just never see these in-game from other opponents. You can take that exploitatively when we are playing the big blind, but I really do think we should look to find some of these super crazy bluffs. If nothing else, it means you get tagged super aggressive so people might make some more heroes against you, but they're also just quite an important part of the strategy."

## Pairing Turns

### General Dynamics

"Then finally we have the pairing turns again. These are usually the lowest equity turns. The in position player is very paired and very ace heavy and they don't improve any of the air from in position and that means that they're generally high equity turns for out of position."

"Also neutralizes the nut advantage. So they are the worst turns for out of position."

### King Pairing Turn

"King is going to be a funny turn because again these pocket tens, nines, eights, and seven x are going to be really good barrels. We again see them just overbetting in this case. I don't want to talk too much about this turn just because it's so specific, but keynote for it would be barrel really wide."

### Seven Pairing Turn

"On the seven turn there's going to be less mergy barreling because king x makes up a lot more of the ranges. We see that even some pretty strong king x are just checking a lot. We also see just an extremely low barrel frequency and that's because of the low equity nature and no real nut advantage."

### Two Pairing Turn

"On the two, there are a lot less trips for both players. So the mergy barreling comes back again, this plays more like a brick but with a way lower frequency, I'd say."

## Exploitative Adjustments

### When OOP Overfolds

"Now briefly I want to, quickly need to unlock the ace, but then I want to compare the frequencies of turn barrels for this baseline sim compared with that sim I locked at the beginning."

"Yeah, we see the overall equity is 43 when the out of position defends too tight on the flop versus 47 and shreds on the right. What this really shows is that, if you think about it, most of the extra folds were some of the weakest hands in the out of position range. That's obviously going to make the turns all lower equity for in position."

"Lower equity means lower barrel in general. What doesn't change however is the nut advantage."

### Strategic Adjustments

"I expect a bigger trend towards overbets too. Yeah, we do see that. Here the low bricks in the default sim and we talked about barreling a small size just because our range needed more protection. We see in the tightest sim the small bets become more overbets on the low turns."

"The overall adjustment we see is lower turn barrel. We see a check frequency of 62 in the unlock sim, say 67 in the lock sim. We also see a higher preference for overbets on most turns."

## Key Takeaways

### EV Impact

"We'll compare that. It has gained the in position player roughly six big blinds per hundred, which is a huge gain when we are making a no adjustment and they're quite simply just overfolding. When a player is making such a significant mistake, it's important not to give it back on later streets."

"These adjustments like barreling less overall and barreling, but more polar are going to be quite important when we face tighter opponents. Thanks guys."