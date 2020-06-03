# Memory-Game-in-Python

# Memory Game
The Memory Game – Introduction
We want to create some cards in order to play a memory game. A memory game is a game in which we try to find pair of cards having the same picture. A card is an object with a picture for the back of the card (is the same for any card) and a picture for the front of the card. Only 2 cards have the same picture (pair).

First, we define what is a picture using string.

After you will create a card.

Create three cards in the main program : two with the same picture on their face.

The Memory Game – full exercise
We have to compute a memory game with hidden pairs of cards. Each player has to find pairs, using the console. The player chose two cards among 20 (or another number). A card has a specific picture on its face and all the cards have the same back. Pictures and Back are defined  as String in a list for example (SUN, CAT, HOUSE, BEAR, DOG, STAR, SNOW, SEED, LAKE, TREE, TRUCK, BACK...).

First display

00[****] 01[****] 02[****] 03[****] 04[****]
05[****] 06[****] 07[****] 08[****] 09[****]
10[****] 11[****] 12[****] 13[****] 14[****]
15[****] 16[****] 17[****] 18[****] 19[****]

If the player do not find a pair, another player plays

00[****] 01[****] 02[****] 03[ DOG] 04[****]
05[****] 06[****] 07[****] 08[****] 09[****]
10[****] 11[****] 12[****] 13[****] 14[TREE]
15[****] 16[****] 17[****] 18[****] 19[****]

If the player finds a pair of cards, it is removed from the console, the player earn 1 point and plays again if there is cards left; Otherwise, the game is finished.

00[****] 01[****] 02[****] 03[****] 04[HOUS]
05[****] 06[****] 07[****] 08[HOUS] 09[****]
10[****] 11[****] 12[****] 13[****] 14[****]
15[****] 16[****] 17[****] 18[****] 19[****]

Display Just after

00[****] 01[****] 02[****] 03[****] 04[----]
05[****] 06[****] 07[****] 08[----] 09[****]
10[****] 11[****] 12[****] 13[****] 14[****]
15[****] 16[****] 17[****] 18[****] 19[****]
You have to define a program using many Classes defined in the same file (Card - Deck - MemoryGame - Player) You can use input()
