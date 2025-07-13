
Study date begin: 9-July
Study date end: ongoing

Current video time:20:54

Mixing is only ok when i expect to get roughly the save EV from the 2/3 actions i'm mixing between, and necessary only in a game with a high visibility (people can take notes on me or observe my tendencies in a live setting).

In this lecture we're going to look at facing a bet and mixing between fold/call/raise, identify the hands that are mixing and hands that aren't (=pure fold/pure call/pure raise)

## Turn cutoff points

### Turn Fold/call cutoff point
Let's start with an example:

Hand 1: CO vs BB SRP, flop Jd,3h,2c flop x/B30/C
Turn 7d X/B75 and now it's on us as BB when facing this. 
https://app.gtowizard.com/solutions?solution_type=gwiz&gmfs_solution_tab=ai_sols&gametype=Cash6m50zSimple25Open3betV2_SimpleOOP&depth=100&gmfft_sort_key=0&gmfft_sort_order=desc&preflop_actions=F-F-R2.5-F-F-C&flop_actions=X-R1.8-C&turn_actions=X-R5.3&history_spot=10&board=Jd3h2c7d

When we face a turn barrel in equilibrium (not against the maniac who overbluffs or the nit who underbluffs but against a competent player), we have a large cluster of hands that are 0EV (indifferent between calling and folding - some are raising but we will ignore this option for now and look only at calling/folding).

We have two thresholds: One threshold for robust hands (=hands that already have SDV) and one for draws(=frail hands).

Guided questions(for hand 1 as BB):
1. Where is our threshold for made hands?
2. Where is our threshold for C/F with our draws? What about my worst flush draws- are they continuing? Why or why not?
3. How does having a diamond affect the ev of calling a pocket pair?


Answers:

1. I need about 29% in EV to continue... Indifference point is 66 when it comes to robust hands

2. While all the flushes continue vs this sizing, vs a slightly bigger bet they don't - so this is sensitive.

3. pps without a diamond call much less: Their outs aren't as clean (one of them will complete a draw), and they block the CO's outs in case he has a flush draw.


Rank the following hands from highest to lowest in EV when calling:
8s8h, Ks7s,KdQd, AcQs,6h6d

KdQd is an excellent flush draw as well as two overpair draw - best EV.
Ks7s has 5 outs to improve to two pair plus in case it's behind - second best
8s8h - above 66 in ev just thx to its rank, since CO can bet for vale A7/K7 it's actually a value beater
AQo - as good as the 66 when it's bluff catching, but it has 6 outs when behind vs 2 outs...
6h6d


### Turn raise cutoff point

Since on the turn we will have a very small value x/r range (77,J7) we will rarely raise with out mixes, and if a hand in a vaccum would fold or raise, it would mostly raise at this spot. If a hand is indifferent between call/raise (for example flush draw) it would mostly call and rarely raise.

Guided questions and answers:


#### Find hands are indifferent between raising and calling?
 
Answer: Jh9h is a surprising example. The main reasons? 

1. It can make some better hands fold (like a better Jx)-we make Jx of villian a bluffcatcher, we should raise this hand only very rarely 
2. worse hands can call (like flushdraws, OESD etc)
Other hands that can rarely raise are 7x, some draws, etc.

#### What hands are indifferent between raising and folding?

Gutshots without a fd,  fds with no sdv raise here pure to often

#### find a hand that is indifferent between folding and raising?

6h4h / 6c5c /9h8h for example (gutshot no diamonds) are hands that mix raising and folding.

#### Find a hand that prefers bluff raising to all other options?
High equity low SDV hands:
 the fds no SDV do it a lot,especially strong combo draws like 54dd,64dd
#### How big of a mistake it is to raise Ah7h?
Not a big mistake, but if solver raised hands like this too often, solver wouldn't be indifferent with hands like top pair because this weakens the raise range of BB.

#### Hybrid raises

Specifically for the current example we want to rarely raise in general since our value bet range is small. But let's think about hybrid raises (raising with middling hands) in general. To do that we need to explore 3 seperate elements of villian's reaction to raise that make it viable:

1. He can fold better hands: KJo with Kd is a pure fold, JTs is indifferent - and that's the top pair region! (when heor's value range is two pair plus, then all one pair hands like QQ and KJ have similar hand strength in absolute terms and what matters are the blockers)
2. He can continue with worse hands: Axdd call pure for example
3. Fold some live hands (KQo with a diamond fold)


### Raising SDV on the river

#### Reploarize: definition:
To raise a bet having condensed our range by calling on an earlier street

Continuing our example hand 1:
 CO vs BB SRP, flop Jd,3h,2c flop x/B30/C
Turn 7d X/B75/C river Ks X/B75/R4X

On blankish runouts like this, the correct raise candidates as a bluff will often be pairs due to interference theorem:

#### Interference theorem:
When I reploarise on the river, I will want to bluff with pairs on blank runouts and flush/straight blockers on wetter runouts.

Question: See our current example, and answer:
What do you think BB's bluff raises are here and how often do i mix them when i hold one? What low SDV hands would be bad bluff raises?

Answer: 

The lower Jx like J8/J6 are good candidates to raise here(!!).
While we're bluffing here we have unblockers to villian's bluffing range and while it doesn't matter that we make him fold his bluffs, it's nice to run less into his calling range.
The idea in general is to block bet/call and unblock his folds.
Another SDV candidate is 43s since we do block 33, but low Jx are my main SDV bluffs(!).

Low SDV hands that are bad to bluff with: 
Missed draws like 98dd (or without a diamond)
QTdd

Remember the definitions:

##### Bluff catcher:
a hand that loses to all villian's value bets and wins vs all his bluffs

##### Range geography:
Locating key milestones in a range that help me see the whole strategy more clearly


And answer the following questions:
1. Identify bluffcatchers that call pure  (Grade A bluffcatchers: +EV calls)
2. Bluff catchers that are indifferent (Grade B bluffcatchers : 0 EV calls)
3. Idenify bluff catchers that pure fold (Grade C bluffcatchers :minus EV calls)

Answer:
1. JTs and JTo without Td are all  positive EV
2. 53dd is indifferent
3. AdTd is a very negative EV bluffcatcher


In general, when exploring the bluffcatchers, I should always look at the EV to estimate how good of a bluffcatcher it is, not the frequency. For example, if a hand always calls but the ev of calling is 0.1 then I can think about this hand as indifferent (Grade B).

#### The mixing pitfall
A common mistake is mixing where i should never be mixing, eg taking an aggressive action because the RNG is very low where action should be pure passive, or taking a passive action because the RNG is high when RNG should be purely aggressive. Mix only if I'm sure a hand is a mix. If I'm not sure, then take the pure action I'm leaning towards! I'm not 'allowed' to consult the RNG when a hand is a pure strategy - any other actions would be a blunder.

As an example, on this river, look at how many few hands mix and most are pure:
https://app.gtowizard.com/solutions?solution_type=gwiz&gmfs_solution_tab=ai_sols&gametype=Cash6m50zSimple25Open3betV2_SimpleOOP&depth=100&gmfft_sort_key=0&gmfft_sort_order=desc&preflop_actions=F-F-R2.5-F-F-C&flop_actions=X-R1.8-C&turn_actions=X-R5.3-C&history_spot=14&board=Jd3h2c7dKs&stratab=strategy_ev&river_actions=X-R19.5

#### The human mixing system
Put everything into 5 buckets, for example between a call and a raise:
Pure call, infrequently raise, sometimes raise, frequently raise, pure raise
Those buckets are 0%,25%,50%,75% and 100%.