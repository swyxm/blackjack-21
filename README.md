**Background:**
The game of BlackJack/Twenty-One is a popular card game that can have many players competing against a dealer. 
What I have programmed is a modified version where it is one player vs. the dealer. 

**Rules:**
The goal of the card game is for the player’s cards to total more than the dealer’s without going over a total of 21 (aka a “bust”). 
Non-face-cards have the value shown on the card (i.e., 2-10), while Jacks, Queens, and Kings have a value of 10. 
Aces are special in that they have a value of 11 by default unless that value would cause the player to bust 
(i.e. have a total greater than 21) in which case the Ace may count as just 1.

While there are many versions of Blackjack, this implementation will only use 1 deck of (52) playing cards. 
The deck will be shuffled, and then two cards will be dealt to the player and dealer alternatingly 
(i.e. first one card to the player then to the dealer, then a second card). While both of the player’s cards are dealt face up (visible),
the dealer’s first card is kept hidden, while their second is visible. The player uses this information to help inform their choices.

Gameplay starts with, you, the player who must decide whether to “stand” (not ask for another card) or “hit” 
(ask for another card in an attempt to get closer to a count of 21, or even hit 21 exactly). 
Thus, a player may stand on the two cards initially dealt, or they may ask the dealer for additional cards, 
one at a time, until the player either decides to stand on the total (if it is 21 or under) or goes “bust” (if it is over 21). 
In the latter case, the player loses immediately, and the game is OVER (i.e., the dealer need not play or take any cards).
