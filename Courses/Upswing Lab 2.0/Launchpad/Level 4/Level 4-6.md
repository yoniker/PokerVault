# Bet Sizing Strategies

## Core Concepts

### Different Hands Want Different Pot Sizes

"Generally speaking, in poker, in any spot, we're going to have a lot of different types of hands and each one of them wants a bigger or a smaller pot."

"An example I like to take is Ace Seven Deuce and something like pocket Sixes or pocket Kings might want to check down or throw one small bet in, whereas something like Ace Seven or Ace King wants a big pot. King high might want to check down, pocket Threes wants to check down, Ace Nine wants a medium-sized pot. So each hand wants to get to a different place."

### The Fundamental Problem

"One of the issues you run into is that if you implement this in a naive way, you're going to be a bit face up. So say you bet all your hands that want a bigger pot and check all your hands that want a small pot. What's going to happen is that when you check back, your opponent is going to get to run you over if he realizes what you're doing."

"This is a basic fundamental issue in poker of how do I make big pots with my big hands, make medium pots with my medium hands, make small pots with my small hands while not giving the game away to my opponent?"

### Two Main Approaches

"Two main ways of doing this. One is the old school way and one we've learned through computers, but both are valid. And it's important that you guys are familiar with both of these."

## The Big Bet Strategy

### Core Philosophy

"The old school way was to have big bets on the flop. The idea is our strong hands want a big pot so we're going to bet with our strong hands and some bluffs, and we're going to check back our weak to medium strength hands."

"If we do this, this is called a polarized betting strategy, it benefits our big hands because they get to get where they want, they don't have to worry about babysitting any small hands or what do the small hands do, and our smaller hands are more in trouble and have to play defense on turn and river after checking back."

### Implementation

"You're going to start out betting big with good hands and some bluffs, follow through fairly often on turn and river. And that's going to be your main money printing line. And when you check back, it's more weak to medium strength hands and it's going to be tougher to maneuver and tougher decisions for you."

### Advanced Protection Concept

"What we've learned from theory and from studying with computers is that when we do check, we need to throw some strong hands in there to keep our opponent from going crazy. This is a bit of a more advanced concept and a lot of players don't do this."

"In most soft environments, non-professional, non-mid to high stakes environments, it's actually not very important to do this because people don't realize this dynamic and they don't attack your check-back ranges enough."

## The Small Bet Strategy

### Core Philosophy

"The small bet strat says, rather than worrying about our big hands first and letting our small hands deal with things later, we're going to worry about our small hands first."

"So what this strategy does is it starts out by betting small with basically everything and your weak hands get to the pot size they want. Sometimes they get a fold, sometimes they get a tiny bet in, which is roughly speaking where they want to be, but they get to do it while escorted by the big boys, by your strong hands."

### Board Texture Example

"So if you look at Ace Seven Deuce, imagine that we bet Eights and Kings and Sixes and Threes really small, but we also bet Ace King really small. So it's a bit tough for our opponent to know what's going on, let this kind of escorts our small hands to the small pot."

### Turn Transition

"What the strategy then does on the turn is it says, okay, you guys got where you want. Now it becomes like the big bet strategy. You take all your big hands and some bluffs, you start betting big on turn and river, all of your small to medium strength hands check, and they see a river and they face the same issue of what do I do against my opponent?"

"But they only need to do it on the river rather than the turn and the river, so you don't need to protect them as much, you don't need to worry as much."

## Strategy Selection

### Range-Based Preference

"A computer is always going to prefer one type of strategy over another, and that's generally based on your range. So if your range has a lot of small to weak hands, it's going to prefer the small bet. And if it has a lot of hands that want to put on lots of money, it's going to prefer the big bet."

### Execution Over Selection

"But the important thing in my eyes is that you understand what you're doing. The differences in how much money you'll make between these strategies is not going to be dictated by necessarily picking the best strategy. So much is just executing it well and understanding what you're doing and playing the appropriate pot size for each hand in your range."

## Reading Opponents

### Identifying Weak Players

"Pay attention to who plays like this. And when he checks, just win the pot from him whether you have something or not."

### Understanding Range Construction

"By seeing the size of a bet someone makes, you can understand what their range construction likely is, what types of hands you're going to see when they check, what types of hands you're going to see when they bet small, what types of hands you're going to see when they bet big."

"No one's going to bet big on Ace Seven Deuce with a pair of Sixes hopefully, whereas they will bet small on Ace Seven Deuce with a pair of Sixes."

## Key Takeaways

"These are both huge topics that you can study for a long time. But hopefully now if someone makes one of these against you, you kind of understand the dynamic of what's going on and that it's actually beyond the bet itself."