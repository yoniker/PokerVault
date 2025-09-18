
My summary: Solvers start at random and play with each other (taking turns) until they reach a balanced strategy. That balanced strategy is a very important foundation. When I watch pros deviate and do something pure during play and explain, I should play close attention- why and how, as this is where the money in poker is being made. I should also think for myself, why is the solver doing what it's doing, and if it applies to my own games and why.


# How Solvers Work

## Core Concepts

### The Toy Game Extended

"Hey guys, what's up? Uh, this chapter is, this video is gonna be an explanation about how solvers work."

"So if you remember the toy game with deuces and ACEs and kind of imagine that this kind of toy game is being played out, but in a more complicated scale throughout the Game Tree of Poker."

"So in, in any spot where you bet, are you betting too weak or too strong in terms of which hands are in there, in any spot where your opponent is facing a bet, is he calling too much or too little? And all of these things are being balanced out except in a much more complicated way than the Deuces ACEs toy game."

"Um, although certainly one that can be conceptualized it as a series of toy games, and maybe we will have videos about that at some stage."

### How Solvers Calculate Solutions

"and yeah, the way solvers work is the computer takes two players with ranges and basically tells them, tells each of them the other guy's strategy, and then has them kind of take turns adjusting."

"So at the beginning of the strategies are kind of random, and then as the solver does its work as a computer does its work, one guy will start bluffing more, the other guy will start calling more than the first guy will start bluffing less and the second guy will start calling less. And things kind of even out to this, these magical mathematical ratios and game plans where you're kind of balanced, right? You're not giving your opponent good options."

### The Purpose of Solver Strategies

"And really at its core, what these programs do is they give you strategies that would be a very strong baseline where it's very tough for your opponent to make any kind of clear, good decision against you, right?"

"Just as though we were bluffing exactly two combinations of Aces for every one combination of deuces, not more and not less, but we're doing this throughout the entire game tree. So our betting range is just the right strength. Our checking range is just the right strength."

### Balancing Draw Protection

"We're checking just enough draws because if you think about it, say you bet every single flush draw on the flop and your opponent knows you're doing that. How would the Aces deuces type of game work is when you checked back, if a flush came in, he would be able to put a stack in with any flush he wanted."

"And then if you knew he's put it whenever you check back and the flush comes in, he's putting a stack in so easily, even with two pair, let's say, then your counter would be, oh, I'm gonna check back some flush draws, right? Since he's putting in too much money."

"And so you start checking back flush draws, he starts putting in less money, and you check back a few less flush draws and it evens out and all the strategies kind of even out in this way."

## Understanding Solver Output

### Reading the Interface

"So, let me explain what we're looking at here. This is the final end product of an evening out of strategies. So here we're big blind versus button. The board is 9 8 7 two-tone."

"And what you guys can see is a chart of hands and above it, uh, color coding for actions. So check or bet 30% size. So bet for a 30% pot size bet, bet 70% or bet 133% pot, which doesn't get used here."

"And then basically what the solver does is it has this evening out right where betting just the right amount of every hand type in every range. Because if we wouldn't, then our opponent would counter us in some way."

### Specific Hand Frequencies

"You guys can see the end result and each hand is colored and if you hover over it, you get to see the exact frequencies."

"So Queen eight of diamonds would always check, pocket ACEs would actually always check if it doesn't have a spade. And with a spade it would check 60 to 65% of the time."

### The Mystery Before Solvers

"And the whole thing might seem very strange to you. It's very mysterious because before people had this kind of software, it was kind of anyone's guess,How, how are you actually supposed to play? Do you check back flush draws? how many? which ones do you? do you ever check back two pair? Do you ever check back a set? Uh, like do you ever bet a set when a flush comes in?"

"And we kind of play these leveling games with each other, and what the computer does is it gives you the end result."

## Hand Examples

### Board: 9♠8♠7♥

"And that's very important to remember. So, uh, yeah, the end result can be quite surprising, right? Like the end result is actually on 9, 8, 7. You check back six, five and ten six fairly often, and this is all in the interest of being deceptive."

"So if we were to imagine, what if I never check back ten six and never check back six five and never check back sets, well then if I checked back and it came a three, my opponent could put his stack in very, very wide."

"And so this is to counter that, right? So everything here is to counter something."

### Turn: 2♦

"So say we click check and turn as a deuce, how much should your opponent be attacking? Let the program run for a second."

"And yeah, what we'll see is there should bet  70% pot and an over bet size, and he gets to bet very wide with a lot of draws, but he still has to protect his checking range, right?"

## Practical Application

### Adjusting to Real Opponents

"And the interesting thing that you might say this, but you might say, well, my, the guys I play with don't do that. Like if I check back and it comes with three, they'll just bet half pot. They won't have any huge bets, they won't be shoveling money and like they're not that aggressive."

"Um, and yeah, basically kind of like the ACEs deuces game, this is teaching you the baseline strategy. But once you know something about your opponent, you can do a lot better."

"So if you know that this is balancing, uh, having good hands in your betting range and in your checking range, but when you check, your opponent isn't attacking as much as he should be, and you can use these programs to see how much should he be attacking, right?"

### Observing Deviations

"So you might, as you look through these, you'll see all sorts of things and you'll be thinking, wow, this doesn't really happen. How does this apply to me?"

"So part of what I want to do in this video is kind of explain to you guys, first of all, there is no need to memorize what these things look like. They're very complicated. Just understand the principle of how this was generated and what it represents. It represents this ACEs versus deuces, optimally balanced situation."

### How Coaches Use Solvers

"And a lot of what you'll see coaches doing in their videos, and I think I mentioned this before, is they'll be kind of, so on 9, 8, 7, they might actually check back some strong hands and say, I'll check this back 40% of the time, right?"

"And here they're trying to mimic what this program is doing, but almost without fail, at some point they're just gonna say, I'm going to, I'm just gonna do this and here's why."

"And that's where they're basically saying, I don't think it's necessarily important to play mixed. We have reached a point where I'm fairly certain what the best play is. And, and really that's where the money in poker is generated."

## Key Takeaways

### Modern Poker Foundation

"But these are very, very useful tools. All of modern poker is based around these outputs, and you're gonna see coaches using them nonstop. So very, very important to to understand."

"And please, if you have any questions about how these tools work or about how to read them, let us know. Uh, and, and we will do our best to answer."

### Theory as Baseline, Adjustments for Profit

"But yeah, this is basically  how is the solution generated? How, how I like to think about it. And what I like to do is I like to take these big picture ideas as much as I can outta this."

"And then as I'm playing, I'll have this kind of, sort of theory oriented style as a baseline. And then as soon as I see a reason that my opponent has ACEs heavy range or a deuces heavy range 

I'll do something very different than what you see here."