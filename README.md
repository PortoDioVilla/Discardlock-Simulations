# Discardlock-Simulations
Simulations of Discardlock games to see the effect of different ratios of discard effects, and maybe different strategies. 

Our basic desire is to see how card draw, approximate discard and such go. Maybe with an evolutionary approach? Look into evolutionary algorithms and stuff.

With the above plan, our programs would run as follows:

Simulate a large number of decks, either manually, or pseudo-randomly by drawing on a database of possible cards
Have these decks play a large number of games against eachother using VERY rigid AI*
Observations of AI are another one of our goals in this project, namely, crafting winning strategies, but it seems like the best way to do this will be to first develop the optimal deck, then develop the optimal strategy. In addition, this deck is pretty trivially easy to play at a decent level, so a simple(relatively speaking) AI ought to suffice initially. Simple rules are like "play on curve if you can" "tap if you can't play on curve" "discard if you have a %chance of activating other effect, or if hand is empty" etc etc.*
Grab lots of data from these matches
*Some data would be winrates, cards drawn, discards, mana distribution of the deck, damage taken, when certain events happen etc. Basically any desired variable can be measured in this way*
Anaylyze this data, use analysis to inform next round of decks
*not sure of what specific methods will be used here, or how the evolutionary aspect will be implemented. At worst, we can just make it up on our own, doing something like top 50% move on, next 50% are synthesis of winning elements, or even completely random or something.

One problem is that the decks will be playing against themselves, i.e. other zoolocks/discardlocks. So we'll have a few control decks too. An inanimate one. One that board clears randomly. One that heals. Combinations of the above. etc.e tc.
