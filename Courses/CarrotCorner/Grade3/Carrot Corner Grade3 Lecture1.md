
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





	


