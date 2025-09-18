# Poker Math and Balancing Concepts

## Core Concepts

### The Mathematical Foundation

"I wanted to make this video just to kind of share some of the background, the mathematical background, that underlies my approach to poker."

"The thing I always think about math in poker is similar to math in cars and that you don't need to know the math of how a car works in order to drive a car and you don't necessarily need to know it in order to build a car. But someone needs to know it and it's certainly interesting and useful. And if you do know it, it's going to kind of help you to understand what's going on, especially when things get a bit tricky."

### The Toy Game Model

"Poker math has a lot to do with pot odds and in all sorts of spots there is a constant risk-reward scenario. Ideally, we look at these things simplified because poker is a complicated game with blockers and equity."

"So we'd look at a simple toy game of I can have Aces or Deuces and you can only have Kings and we're on the river and I have a pot-size bet behind."

"The way the toy game works is if I make a pot size bet, I'm risking, say, a hundred dollars to win a hundred dollars. If you fold over half of the time, I'm going to bluff all of my pocket Deuces because then they're making money. If you fold less than half of the time, I'm never going to bluff my pocket Deuces. So there is a balancing point."

### Pot Odds and Balancing Ratios

"A lot of what you see professional players do is they try to reach these balancing points where you call just enough Kings to not allow your opponent to get away with any shenanigans and then you're kind of indifferent to what he does."

"Then, the counterpoint to that is the guy with Aces and Deuces, he's giving the guy with Kings two to one pot odds. So the guy with Kings, if when he calls and loses to Aces he loses a hundred; when he calls and wins versus Deuces he wins two hundred because there's the pot and the bet. So he's allowed to win one third of the time and we're allowed to have one Deuces combo betting for every two Aces combos betting."

"You can model this in a solver or you can do it with math and equations. People knew this stuff way before solvers."

### Imbalances in Practice

"This kind of underlying principle is beneath the surface of a lot of what's going on in poker and a lot of how people make decisions. And the reason for that is, like we said, there's this perfect balancing point. But in practice poker is so complicated..."

"Your opponents almost always, and this goes for absolutely everyone, guys, even the very best players, they're almost always imbalanced. They're calling too many bluff-catchers, they're folding too many bluff-catchers, they're bluffing too much or they're bluffing too little in almost every single spot."

"A lot of the dance in poker is to develop a good intuition for how to get your opponent to fold too much when you're bluffing, to call too much when you're value betting, how to fold too much when he's value batting, when he isn't bluffing enough and how to call too much when he's bluffing too much."

### Bet Sizing Mathematics

"And these kind of numbers are kind of the underpinning of that. How often do you get to fold to a ten percent river bet? What's the value-to-bluff ratio there? And same for a third pot river bet, a half pot, pot, a 2x pot."

"And what you might see, kind of surprisingly when you look at this chart, at ten percent bet you hardly ever get to fold to, you need to call almost anything. But also the other guy almost never gets to bluff. This creates an interesting situation where it's so, so easy to overbluff for anyone who thinks about bluffing. It's also kind of easy to never fold. So yeah, kind of two balancing points there."

"And ten percent pot bluffs are often very useful in a spot where a lot of your opponent's range is just very weak and it's difficult to put you on a bluff, so they might just fold hands that they're not really supposed to. That's when it would be useful as a bluff."

### Overbet Mathematics

"Another interesting thing you might notice is that while versus a pot sized bet you fold half the time, versus a 2x pot bet you don't fold seventy-five percent of the time, it's just sixty-six. That's how the math works. It would need to be a 3x pot bet, I think, to make you fold seventy-five percent of the time."

"And this kind of creates a situation where a lot of people fold too much to overbets just because of how their intuition is configured. Like, 'this is twice as big, I should fold twice as much'. Not how it works. You actually, if it's twice as big, you fold one and a third as much. Versus a one-and-a-half-x pot you fold sixty percent."

"So, 'one and a half times as big, you fold one and a half times as much.' No, not really. That's one of the reasons big bets tend to overperform as bluffs versus less experienced opponents."

## Hand Examples

### Example 1: Draw-Heavy Board

"Where can this math come into play and how can we take advantage of it? A good example is a hand reading example of, say, you bet the flop on a Jack Eight Six, there are a million draws. Your opponent calls. Turn is a Deuce, goes check check. River is an Ace."

- **Flop (J♦8♣6♠):** "You bet the flop on a Jack Eight Six, there are a million draws. Your opponent calls."
- **Turn (2♣):** "Turn is a Deuce, goes check check."
- **River (A♦):** "River is an Ace. Say, fires a half pot bet."

"You might be like, 'okay, let's count how many busted draws are there? One, two, three, right? Seven Five, Seven Nine, Ten Nine, Queen Ten, Queen Nine, so many busted draws.' And you'll be like, 'I think this guy's going to bluff all of those. How many value bets are there? How many hands is he going to bet with just a Jack or does he need an Ace? How often does he have it?'"

"And you kind of count combos. It's a very high level mathematical thing what I'm saying. But as you get experienced, you kind of do this intuitively."

"Or like, 'wow, that's a whole lot of bluffs. Not a whole lot of value bets, he's going to need to limit his bluffs. He's going to need to actually give up some Queen highs, maybe even some Ten highs.' And you think about your opponent, you're like, 'is this guy ever giving those hands up?' And if the answer is no, he's bluffing too many Deuces in the original Aces-Deuces toy game and you make lots of hero calls."

### Example 2: Three-Bet Pot on A High Board

"The opposite spot would be, let's say the guy three bets you and it comes Ace King Ten."

- **Flop (A♦K♣T♠):** "He starts betting"

"He starts betting and you're like, 'it's actually kind of hard to find bluffs here. The three betting range is rich in high cards. So what's he bluffing with? Is he bluffing with Jacks? Is he bluffing with Five Six suited with no flush draw?' And then you might be like, 'oh, I think he's actually going to have too many of 'the Aces' hand here.'"

"And a lot of poker is figuring out this balancing act of when does he bluff too much? When does he bluff too little?"

## Range Splits and Imbalances

### Using HUD Stats

"This is a large part of the reason that people use HUD stats. HUD stats are something I don't use too much these days because in the games I play people have gotten a lot better, so it's actually more noise than it is data since people are generally fine at most things."

"It used to be, however, people were very imbalanced with their HUD stats, which means there were a lot of places where they were folding too much, where they were too strong."

### Checking Range Weakness

"And the nice thing about poker is these things kind of go together. So, a leak that a lot of players used to have and still have is that when they checked, their range would be too weak and when they bet, their range would be too strong."

"I just knew that when they checked, their range was too weak. How did I know this? Because I noticed that the statistic was when they checked and I bet they were folding too much, right? Just like the river game, if they checked to me and I bet half pot, they only got to fold so often and they were clearly folding a lot more than they should (MDF)."

"So I was like, 'okay, I'm going to attack here.' But for every place where there's a weakness, there's a place where there's a strength. They're not just weak all over. If they check, too weak. They bet, too strong. This is just general deduction. So if they bet, maybe get out of the way a bit more."

"This is a very common player type in live games and at low stakes online. Lot of mid stakes, probably."

### Range Splitting on Multiple Streets

"And there are a lot of places in poker where you split your range. If you think back to the range-bet versus big-bet-flop decision, if you big-bet flop, you're already splitting your range on the flop."

"And you ask the question, 'are you actually checking back strong enough?' And the answer for most professional players in two thousand twenty-five is no. They're checking too weak and after they check you can attack, which means that they are betting too strong. So these things go together."

"If they range bet, then the split happens on the turn and very often it happens in the same way, where the betting range is a bit too strong and the checking range is a bit too weak."

## Key Takeaways

### The Intangible Nature of Poker

"So a lot of poker is very intangible. Because at the very basic level, you're learning how to play your hand and how to navigate to the correct pot size and how to narrow your range, how to play this Aces-and-Deuces game in a reasonable enough manner, right?"

"I'd want you guys playing it in a reasonable enough manner where it's not super face up that you're a nit, or you're a calling station, or you're a spazzy bluffer. We want them to have some doubt and feel like when they play against you, they're not really sure what's going on. They're not sure if you're bluffing too much or too little, right? You want your opponents to kind of be on their toes and not have easy decisions, so we practice it playing this balancing game."

### Finding and Attacking Imbalances

"But the counterpoint to that is that you should always be looking out for, and the better you get at balancing, the more you're going to be able to intuitively spot where your opponents are imbalanced and attack that."

"And what you're going to see in a lot of live play videos, you're going to see coaches do kind of a combination of these two things. So, on the one hand you'll constantly hear them randomize..."

"Randomization is something that's done purely for this Aces-Deuces type of game that gets played throughout the game tree in various iterations. At the very, very basic toy game level we're doing this everywhere."

### Learning from Professional Play

"And as we get better at it, we spot the mistakes our opponents are making and then kind of comfortably, like a professional athlete, we're like, 'oh, I'm actually going to on purpose bluff too much or bluff too little in a spot, or fold too much or fold too little.' In the live plays, pay very close attention to this."

"Whenever you see a coach make a decision, a lot of the times they're randomizing. And whenever they're randomizing, treat that as an exercise in balance. So watch it and ask yourself, 'does this make sense?' This is kind of mixed, this is my basic fighting stance."

"But really pay very close attention to the spots where they don't randomize, where they say, 'I'm just going to call. I'm just going to bet. I'm just going to bluff for this size'. Because this is where, whether they verbalize it or not and whether they're consciously aware of it or not, this is where a lot of their profit comes from."

"And a lot of the guys you're watching are very successful poker players, so all of them are going to be reasonable at the dance of balance and they're going to make some errors, but the errors are not important. They're dancing... balancing in a way where it's not clear to an outside observer."

"And what I'd like you to pay attention to as students, as well as the balancing act, which you need to get reasonable at, is where and why they're doing something else and what thought process they're using to do it."