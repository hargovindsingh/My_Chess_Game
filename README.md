# README
Welcome to my __chess game__ .

Built using: __JAVA 8__ with a __JAVAFx ui__.

Modes:
1) Player vs. 	Player
2) A.I. 	vs. 	Player
3) A.I. 	vs 		A.I.

Export Format supported: FEN or PGN.

## Table of Contents
1. [About the game](#about-the-game)  
	1.1 [Before you start the game](#before-you-start-the-game)  
		1.2.1 [The AI opponent](#the-ai-opponent)  
		1.2.2 [Chess notations](#chess-notations)  
2. [How to get it](#how-to-get-it)  
	2.1 [How to import it to Eclipse IDE](#how-to-import-it-to-eclipse-ide)   
3. [How to run it](#how-to-run-it)  
	3.1 [Within the IDE](#within-the-ide)  

## About the game
### Before you start the game
![screenshot of settings screen](https://github.com/hargovindsingh/My_Chess_Game/blob/master/chess/src/com/chess/resources/img/chess_screenshots_settings.png)

You can choose:  __Color(Black/White)__, __Difficulty Level (A.I. range is about 1600 elo)__, __Pre-Load(Continue games from the middle)__.

### The game
![screenshot of game](https://github.com/hargovindsingh/My_Chess_Game/blob/master/chess/src/com/chess/resources/img/chess_screenshots_game.png)

#### The AI opponent
Algorithm Used: Minimax algorithm with alpha-beta-pruning.

On the highest __difficulty setting__, recursion depth is set at 4,lowest __difficulty setting__ has 0 depth.

#### Chess notations
Why Use Chess Notation?
Competitive chess games, even at a low level, require players to write down their moves using chess notation. However, you may ask yourself why you need this descriptive notation at all. When you play other board games, you don’t notate your moves!

There are several reasons in chess, however, that makes it obvious as to why it is so useful. The most apparent reason is that you are not allowed to participate in chess tournaments if you do not know how to notate correctly.

Why is that? If there is a problem in a game or a dispute, the arbiter, who is there to help you in these cases, must be aware of the progression of the game. It makes it easier for any arbiter to look at a scoresheet, which is clear evidence than to rely on the memory of the players.

####The Chess Pieces
Chess notation also uses abbreviations for each soldier in the army, using capitalized letters.

King       = K

Queen   = Q

Bishop   = B

Knight   = N

Rook      = R

Pawn     = no notation

The abbreviations are fairly straightforward to remember. In most cases, they are simply the first letter of the piece’s name.

There are two exceptions. Knights are abbreviated as “N” because “K” is already taken by the king.

Pawns aren’t assigned any capitalized letter – it would be more consistent if we used “P” for the pawn, but for some reason, we don’t… maybe to save ink. Pawn moves are indicated using only the square name.

Fortunately for English-speakers, the same capital letters for chess pieces are used all over the world, allowing us to easily understand foreign games without needing to refer to a translation dictionary. Germans call a bishop a “Läufer”, for example, but write it as “B” in chess notation.

Putting It All Together
Chess notation combines the chess piece moved with the new square it has moved to on the chess board. A bishop moving to the c4 square is written as “Bc4”. A pawn moving to the e3 square is written as “e3” (remember, pawns have no capital letter). A queen moving to the a7 square is “Qa7”. You get the idea.

Moves are usually written in pairs, showing both the White and the Black move – for instance, 1. e4 Nf6 shows that White used its first move to push a pawn to e4, and Black responded by developing a knight to f6.

####Captures
Capturing an enemy piece sees an “x” placed between the piece moved and the square the captured piece was upon. So, if a king captured a chess piece on e1, the notation would show “Kxe1”.

The pawn captures require us to show which file the capturing pawn came from – so a pawn which was on h3, capturing on g4 would be “hxg4”.

## How to get it

Clone the repository with:

    git clone https://github.com/hargovindsingh/My_Chess_Game your-target-path

### How to import it to Eclipse IDE
1. Go to ``File > Import``
2. Pick ``Maven > Existing Maven Project``
3. Now, navigate to the directory you cloned it to
4. Pick the root directory ``chess`` and click ``Finish``
5. The project will be opened and build

## How to run it

### Within the IDE
You can directly run it within the IDE.

In case you experience weird UI behavior (buttons look weird), it may be a DPI scaling issue known to occur with Windows 10 notebooks.
To fix it, do following steps:
1. Import Project
2. Simply run the project as a JAVA application from Chess.java

