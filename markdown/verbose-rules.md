# Oracle Chess Rules

1. The _Oracle Chess_ is a novel chess-variant, a deterministic board game for two players based on Chess.
Apart from substantial similarity to the canonical Chess, in the game we introduce several features:
First, rather than solid pieces, there are bodies and souls which may separate;
second, we allow rebirth of men on certain circumstances;
third, in place of Queen, there is the new piece &mdash; Priestess, and its different induced forms, as follows.

	- Core definitions, in this document, are numbered to let them stand out, while explanatory commentary are interspersed, like now, and marked with a bullet point.

1. In playing the game, two players move _tokens_ on a _board_, take them away from it, or take them back on it.
They are associated respectively with two colors, _White_ and _Black_.
They move, alternately, tokens pertaining to their own color, starting with White.

1. Each move takes a _tempo_.
Two tempi is called a _round_.

1. There are two kinds of tokens, _bodies_ and _souls_, and there are several _classes_ of either of them.
A body is associated with either White or Black, but a soul is not.
All bodies of the same class and color is identical.
Likewise, all souls of the same class are identical.

1. A class of soul may either _match_ or _mismatch_ a class of body.
A particular instance of soul may _bear_ a particular instance of body, so that they are _united_.

1. A compound of one body and one or more matching souls is called a _man_, and the body of a man is said to be _living_.
A compound of one body and one or more mismatching souls is called a _ill-suited body_.
A body without a soul is not said to be a man, and we also call it an _lifeless body_.

	- I promise the whole idea is really easy, but I am sorry that we have to introduce a few terminologies to be more precise.

1. There are the following classes of bodies: _Lord_, _Priestess_, _Chariot_, _Elephant_, _Horse_, and _Soldier_ body.
There are the following classes of souls: _Lord_, _Chariot_, _Elephant_, _Horse_, and _Soldier_ soul (without Priestess's).

1. A Lord, Chariot, Elephant, Horse, and Soldier body (except for Priestess) each matches the corresponding class of soul.
A man is also called by the class of its body.
Thus, a Lord body matches a Lord soul, and the compound is called simply a Lord, likewise Chariot, Elephant, Horse, and Soldier are called as thus.

1. The _board_ is of square shape, spanned along two _directions_, extending for 8 _units_ from left to right, and from back to front.
Thus it is made up of 64 discrete _squares_ on it, which are numbered from _a_ to _h_ in the horizontal direction, and from _1_ to _8_ in the vertical direction.
Each _squares_ may either be _empty_, or may accommodate one body and one soul it possibly bears.

	- That is, we use just the chessboard, and squares are numbered as usual.

1. In the beginning of the game, the White (respectively, the Black) has a Lord placed on _e1_ (_e8_), an lifeless Priestess on _d1_ (_d8_), two Elephants on _c1_ and _f1_ (_c8_ and _f8_), two Horses on _b1_ and _g1_ (_b8_ and _g8_), and two Chariots on _a1_ and _h1_ (_a8_ and _h8_).
The White (the Black) has eight Soldiers placed on _a2_, _b2_, ..., _h2_ (_a7_, _b7_, ..., _h7_).
Except for the lifeless Priestesses, all bodies are living.

	- All men but Priestesses are placed on its analogous starting square in Chess, and Priestesses takes up the Queen square.

1. A _follower_ body (or soul) it is either a Priestess, a Chariot, an Elephant, a Horse, or a Soldier body (or soul).
A _warrior_ body (or soul) is either a Chariot, a Elephant, or a Horse body (or soul).

1. A Priestess body matches any warrior soul, and may bear one, two, or three of them, which need not be of distinct class.

	- Thus, a Priestess-body may bear, for example, a Chariot soul and a Elephant soul, or all of Chariot soul, Elephant soul, and Horse soul, or even two Horse souls, among 20 cases.
  But usually we expect it to bear distinct souls, which make up 8 cases.

1. When a token or tokens _move_, it or they _go_ or _capture_, which we now examine.

1. A soul may _go_ alone from one body which bears it to another lifeless body, where the new body must be of the same color with the old body.
A man may also _go_ from a square to another empty square.
Such moves are legal when the initial square (that the old body lies on) and the final square (that the new body lies on) satisfy certain relation completely dictated by the class of the moving soul.
The action takes a tempo.

1. A Lord soul (and so a Lord) goes for either zero or one unit in either direction.

	- They move exactly like the King in Chess.

1. A Chariot soul (and so a Chariot) goes for several units in one of the directions, provided that none of the squares which lies on the line that passes through both initial and final squares, is occupied.

	- They move exactly like the Rook in Chess.
  Recall that they can be blocked.

1. A Elephant soul (and so a Elephant) goes for several units in one of the directions, and the same number of units in the other direction, provided that none of the squares which lies on the line that passes through both initial and final squares, is occupied.

	- They move exactly like the Bishop in Chess.
  Recall that they can be blocked.

1. A Horse soul (and so a Horse) goes for two units in one of the directions, and one unit in the other direction.

	- They move exactly like the Knight in Chess.
  Recall that they cannot be blocked.

1. A Soldier soul (and so a Soldier) goes for two units in one of the directions, and one unit in the other direction.

	- They move exactly like the Pawn in Chess when they move.

1. A lifeless body cannot go to another square, nor can a ill-suited body go.

	- It is helpful to think the soul drives the bearing body to go when they match, while the soul is able to go over bodies by itself.

1. A man may also move to a square already occupied (by another man, another ill-suited body, another lifeless body), where the occupying body must be of the opposite color with the man.
When this happens, the occupying body and the soul it possibly bears, leave the board.
We say the man _captures_ the occupying body.
The action takes a tempo.

A Lord, a Priestess, a Chariot, an Elephant, and a Horse (except for a Soldier) capture the same way they go.
Namely, the initial square and the final square satisfy the same relation as they are when it is allowed to go.
When a Soldier capture, it moves horizontally for one unit, and forwards for one unit.

   - These are just same as Chess.

1. When a body leaves the board, it goes to the _earth_, and it switches its color from white to black, or from black to white.
When a soul leaves the board, it goes to the _underworld_.

1. When a Lord goes to an empty square, a lifeless body taken from the earth may be _dropped_ on the square it formerly occupied.
The body must be of the same color as the Lord.
Other man may not do so.
The action takes a tempo.

1. When a Priestess is able to bear another soul, it may _fetch_ a soul taken from the underworld, and bear it.
The action takes a tempo.

1. Therefore, the total number of bodies present at the board and those absent from the board (thus in the earth), is conservative throughout the game.
In a similar fashion, the total number of souls present at the board and those absent from the board (thus in the underworld), is conservative throughout the game.

Promotion

1. In each _position_, each body is of definite color and either lies on a certain square or stays in the earth, and each soul is either being borne by a body or stays in the underworld.

1. Either one of the players wins the game, or the game ends in a draw.

1. A player wins the game if Lord soul of the enemy is about to be captured in the next round, and no move can avoid the capture.
In this case, the other player is said to be _checkmated_.
A player also wins if the other player _resigns_, or _lose on time_.

   - Here I do not rule out the possibility that a Lord body is captured, but the Lord soul has not been so.

1. The game results in a draw when a position repeats for three times within three rounds.
The game results in a draw if, within 32 rounds, no man captures and no soldier moves.
A draw also occurs if two players mutually agree so.