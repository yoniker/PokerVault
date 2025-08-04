
## 1.1 Pseudo GTO execution

I'll get a framework of how to execute pseudo-GTO.
We can't play perfectly balanced - but we can get close to it.

What does it mean to play GTO? It means to play an unexploitable strategy.
The assumptions of GTO are:
1. Opponent is clairvoyant (=know exactly my entire strategy)
2. Opponent is perfectly adaptable (no matter what I do, he can maximally exploit it)
This GTO opponent is the NEMESIS (a term taken from the book "the mathematics of poker"), a really scary opponent, he's perfect.

However, my opponent is NOT the nemesis, it's a human. So why do I need GTO strategies?
The main reason is because I can then become an excellent expoliter - once I see how balance looks like, I will be able to identify leaks in my opponents' strategy.
Other reasons are - on nodes that are very frequent (preflop/flop and some turns), maybe I don't want to play exploitative strategies, or when I play vs someone who is better than me, or when someone countered my exploits and now I want to revert back to balanced play.

So- How do we do it?
First, we need a system. Without a system, we can "play by feel", which is for sure very error-prone. Saulo looked for an efficient system (lower effort). He looked at a chaotic solver output of 4 different bet sizes and mixing of stuff like 83%/17% which are also hard to remember, and asked what he can remove so that most of the result (unexploitable stratagy) will remain.

So first - we can use only one bet sizing for the flop and the turn (per flop texture and then turn texture).
Second - we can't remember exact frequencies, so we use the bucketing system.
0,20%,40%,60%,80% and 100%, or 0% 25% 50% 75% 100%. We put any given hand into a bucket. So for example, if we use the 5 buckets system, a hand can be:
-never bet (0%), infrequently bet (25%),sometimes bet(50%),frequently bet(75%), or always bet(100%).

So the system's structure is:
1. One size per node 
2. 5-6 frequency buckets
Bet size is taken from a predefined pool of bet sizes that I decide on. Saulo recommends having a small, medium and large. Sometimes the SPR allows for a "tiny" bet sizing as small (10%), and very large (overbet). The exact sizing don't make any difference, it can be 12%,25%,50%,100% and 200%, and it can be 10%,30%,70%,150%,300%. As long as I study with those bet sizes so I'll know how to execute well.

This leads to reduced decision fatigue, and increased likelihood of accuracy: If I have only 3 flop bet sizes, then even if i picked at random I would be right 33% of the time :)
So, when I execute/study, my goal is to find:
1. The appropriate bet sizing (from the pool of predefined sizes)
2. The appropriate bucket for my hand (from the pool of predefined 5 buckets)
When I pick the bet sizing/frequency, I need to think about what region of my opponent's range I make indifferent. When it comes to indifference, the more of the range I make indifferent the better, and the stronger the hands I can make in different the better.