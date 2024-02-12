# small_games

-----------------
# Thoughts
-----------------

## Blackjack
- Cards can be either a finite list with pop, or 52 unique object
- Cards chosen needs to be in a random order
- Shall the cards be shuffled every round or until none are left?
- Player hands can be dealt with as a list
- Dealer hand can be handled by only printing the first element in the list until showdown
- In case of hitting 21 or over 21 needs to immediately stop round and run results
- Need to ensure that Jack, Queen, and King is not represented as just 10 for special rules
- Check for special rules possibilites while len(list) = 2
- Need to account for Ace being both 1 and 11, and if 11 over 21 account only for 1
- Dealer stops at soft 17 or hard 17?
- Split: Player have two lists which they need to be able to choose from independently
- Double up, can be allowed after split
- Generally I will disallow double up and points from the start
- Shall I give warnings in case of weird moves?


## Mastermind/Wordle
- Take four random colours of red, yellow, green, blue, white and black or take a random element in list of words
- In case of Mastermind, will I allow easy mode by making the colours unique?
- In case of non unique colours, all non correct positions can be summed and compared to the sum of non correct positions of same colours in secret combination
- 
