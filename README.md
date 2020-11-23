# Blackjack card game 🃏

- Repository: `js-blackjack-card-game`
- URL BeCode Repository : [Casino-Royale](https://github.com/becodeorg/gnt-verou-1-26/tree/master/2.The-Hill/2.Casino-royale).
- Type of Challenge: `Learning Challenge`
- Duration: take your time
- Deployment strategy: Github page
- Team challenge : `solo`

## The Mission
Make the card game [21 (blackjack)](https://en.wikipedia.org/wiki/Twenty-One_(card_game)).
We will focus on the base rules for now:
    - Every card represents its numeric value. Special cards count for 10, ace is just 1
    - You automatically lose if your total value is 22 or higher
    - Ultimate goal is to reach 21 (solo game) or to have a higher hand (21 or lower) than your opponent (playing vs computer)

### Must-have features: phase 1 - solo game
- The player can request a new card
    - You'll need to create a variable containing possible card options (focus on the numbers, we don't really care about the symbols for now)
    - The drawn card is shown on the screen (just a number to represent the card is enough for now, special cards can show as 10)
    - If a card is drawn, that one disappears from the pool
    - What html element can be best used to display a list of the users cards?
- Win conditions (21) or lose conditions are checked (22+)
- If player has won or lost, the game ends and a message is showing
- If not, the player can request a new card
- Add some basic styling

### Must-have features: phase 2 - for real this time
- We introduce a new player: the dealer (= the computer)
    - The dealers hand is always visible
    - The player can stop (with a lower hand than 21), after which the dealer tries to beat him (= have a higher hand)
    - After the players turn, the dealer can decide to have one more card if the total amount is lower than the player
    - The dealer wins in the event of a draw
    - If the player stops, the dealer gets as many turns as needed to either win or go bust
- Add a basic casino style theme to the page

### Nice-to-have features
- Use extended styling to add a casino style look and feel (you can go all 007 if you want)
- Instead of just using number for cards, use "real" cards: both a type and a number and use the actual name of special cards (king, queen, ...). What JavaScript concept can you use to store this info?
- Use the images of cards. (very hard!)

### Extra features: go wild (hard)
- Make a gamble mechanic, every user starts with X chips, and before each round we ask what he wants to gamble. If both the PC and the player bust the wins go to "the house".
