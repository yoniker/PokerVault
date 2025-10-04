# Flop Play: Range Betting Principles

## Core Concepts

### Why Range Betting Works

"Range betting naturally exploits human tendencies pretty often. What I mean by that is that most humans will overfold a little bit but also under-raise. The natural exploit for someone who overfolds and under-raises is to bet more often. So the range bet strategy is just a natural exploit to that."

### Simplicity as a Strength

"The next major perk of range betting, it's really simple. This has a couple of main benefits. The first is that when we play a really simple flop strategy, we can spend a lot more of our time studying turns and rivers. In a game as complex as poker, it's pretty important to study spots in-depth enough so you understand the interactions rather than just learning the good flop strategies. A simple flop strategy where you play the later streets well is always going to be a lot better than a complex flop strategy if you don't understand the later streets."

"The first benefit of it being simple is you get to study deeper. The next major benefit of this is you make less mistakes in game. Now I'm pretty vulnerable to this myself. I find if I'm trying to play mixed strategies, I often make autopilot mistakes, particularly if I have a few tables up. So the strategy being simple is just a real benefit in my opinion."

## Board Texture Analysis

### How the Solver Defends vs Range Bets

"What I have below is just a few screenshots of how the solver defends versus a one-third range bet and this is big blind versus button. I'm just going to go through a few boards and show you how tough it is to actually defend versus the range bet."

#### A♠8♦3♠ Board

"The first board here is ace eight three and we see hands in this kind of box here. These are hands like jack ten with one spade and ten nine with one spade, and these are always continuing on the flop. I think these are really quite difficult and I think most players will overfold with these. Then we see some of these weak gut shots and hands like three two, check raising essentially always. I also think this board will be under-raised and the natural exploit versus someone who over-folds and under-raises is to bet more often and our range bet strategy should perform quite well."

#### K♣4♦3♠ Board

"The next board I have up here is king four three and again we see some really wide floats. This time these are two undercards without a backdoor flush draw and these are calling pure. We also see ace highs never folding, which is kind of crazy. This whole chunk here, these are just two undercards with a backdoor flush draw and we see they're either calling or raising always. This segment of blue will be the hearts combos where they don't have the backdoor flush draw. We even see our queen two and jack two with the backdoor continuing as well. So yeah, again, this is probably over-folded and under-raised, so pretty good to range bet this sort of board."

#### J♣8♠2♠ Board

"The next board is jack eight two and this one looks a little bit more natural. We still see some of these wide floats from specifically king ten and some of these lower backdoor flush draws are pretty tough to find I would say. In general, this board looks a bit more natural looking, but I still think that we'll see a bit of an under check raise. I see weak gutters like nine seven are raising a lot as well as some of these low two x. I think this boards probably a bit under-raised and probably a little bit over folded too. So again, our range bets reasonable."

#### Q♠7♦2♠ Board

"Finally queen seven two with a suit and again we see a similar pattern. These two undercards with backdoor flush draw are just continuing always and we're calling a lot of ace x here as well. So same idea as this but probably a bit under-raised and over-folded. So range betting is pretty good."

"The idea of this part is just to give you an idea of how tough it is to defend versus the range bet and just show that it's usually a smart exploitative strategy while also being a good strategy in theory."

## Strategic Framework

### Testing Different Strategies

"Next I want to walk through a spreadsheet I've made. There has been another module on this, I'll just mention this first. Doug and Ryan looked at spots and decided whether you could range bet based on the frequency of the spot. I've gone kind of a different way where I've essentially asked the solver the question and I've got this spreadsheet which I've made and I'll quickly walk through it."

"So down the middle here we have the ranges. This is the in position range, it's a button range. These mixed strategies aren't going to matter too much and the general shape of this range is very similar to the upswing ranges, so it shouldn't matter too much. Similarly, this is the big blind defend range. It's a similar shape to what we'll see in game and the specific hands don't matter too much."

"So these are the ranges and then on the right here we have the EVs. I've essentially offered the solver three strategies. So I've offered the solver a strategy where it range bets one-third in position. A strategy where it plays a 30% mixed strat and a strategy where it plays a 70% mixed strat. The goal here is to essentially give the solver three strategic options and see how each of them perform."

### Analyzing Results

"I've taken these numbers here and essentially compared them. What these numbers show is how much that strategy loses on given boards. For example on the four two two we see that a 30% mixed strategy and a 70% mixed strategy don't lose any EV. They are zero, whereas the 30% range bet loses quite a bit here, 7.2 big blinds per hundred. That's because this four two two board is really poor."

## When NOT to Range Bet

"There are a few rules we can use to work out whether we can range bet a board or not. It's better to look at what boards we can't range bet and that's because you can range bet most textures. If we look down this left column, it's very, very green. This kind of shows that it's a pretty good strategy across a lot of textures."

### Three Categories of Poor Range Bet Boards

#### 1. Boards Where Our Range Misses

"We can see the textures which we can't range bet and they kind of fall into these three categories. The first textures where lots of our range misses. Now if we think about this kind of practically, if a lot of our range misses, so this is usually boards where there's three cards below the nine say, a lot of our range is high card. If we consider that, a lot of our strategy will be to do with realizing equity with all the air in our range. So a really high-frequency bet doesn't tend to make sense because it can be punished by out-of-position, check-raising aggressively. That's why we see all of these low boards colored a bit red in the solver and they're not very good to range bet."

#### 2. Neutral or Disadvantageous Nut Advantage

"The next kind of board that we can't range bet is boards where the nut advantage is kind of neutral or we've got a slight disadvantage. So that's boards like these lower paired boards. So the four two two is an example. Out of position has a bit more two x than us. They've got a little bit of a nut advantage and that means that out of position could punish us for a high-frequency bet and they tend to not make too much sense."

"That's also why we see a board like nine eight five being a poor board to range bet given that out of position has some six seven offsuit here where in position doesn't. That means they have a bit of a nut advantage and can again punish us if we bet too wide."

#### 3. Big Bet Strategy Boards

"The final type of board, which is poor, is one where the big bet strategy is really good. So there's a few examples here. One is the ace king queen. We've just got such a big advantage at the very top of the ranges. We like playing a big bet strategy here. I confess that I'll play the range bet here anyway just because I haven't studied the big bet."

"Another good example of this is king nine six. This board just has tons and tons of straight draws. So I think the solver likes playing a bit of a bigger bet to punish all of that middling equity."

## General Rules for Range Betting

"If we look through the ranges, essentially any board which is ten high or higher is going to be reasonable to range bet. If we look through all these, ace high boards are good, except the ace four two. This texture, it both misses a lot of the in position range, but also the nuts are symmetric. The main nutted hands are based around this region. The bottom of the ranges where the out-of-position player just has a few more of the cards there to this."

"We look down, most of these ace boards are reasonable. All of the jack high boards are reasonable to range bet. Similarly, the king high boards are all reasonable except these two monotone boards, queen highs, all reasonable to range bet except another monotone board. Then ten highs are reasonable as well other than this monotone board."

"What we can see a pretty good general rule is if the board's disconnected and it interacts with the offsuit hands in our range, we get to range bet. Disconnected here, I'm just referring to no straight is possible, but we can see it's actually pretty reasonable even to range bet some of the straight boards like ten seven six."

## Key Takeaways

"The way I approach it is essentially if the board doesn't meet any of these reasons, I would just range bet it in game."

### High-Hanging Fruit: Sizing Adjustments

"I've written here high-hanging fruit, smaller range bet size, and that's because there are some textures where it makes a lot of sense to range bet smaller and that's usually where the nuts run closer. Generally, these monotone boards might be okay to range bet for say a fifth pot or a quarter pot. I'm not going to go into that in this module. I'm going to try and give a deeper view of more common spots, but it's something you could look at if you were interested in going a bit deeper."

"Thanks for watching and I'll start talking about turn play in the next video."