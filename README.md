# Chess Memory Match
Memory game inspired by [memory match for iphone](https://apps.apple.com/ca/app/memory-match-brain-training-memory-games/id1172020731). Memorize the location of chess pieces in a grid.

## Roadmap

* Menu for customization
* Board size
* Number of pieces
* Levels
* increase/decrease of pieces on success/fail
* numbers of different pieces
* time before pieces disappear
* time until solution reveal

## Original README
The program works by having two decks: a visual deck and a hidden one. Upon game start, the visual deck holds the backsides of all the cards, and the hidden deck holds all the card faces. As the user finds matches, the two matching card faces from the hidden deck replace the card backs of the visual deck, thereby making them permanently visual. By the end of the game, the hidden deck has become the visual deck - all card faces are shown. When the user restarts the game, the visual deck is reset to the card backs, and a new, randomized hidden deck is created.

## Credits
* Originally a card game by Nathan Carmine, see [ncarmine/Memory_Match](https://github.com/ncarmine/Memory_Match)
* python 3.8 and [pygame](http://pygame.org/).
* Original card images from http://colome.org/ and spliced to make individual cards.
