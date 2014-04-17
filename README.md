ew

As with any of the "Project" Assignments your are encouraged to work with a partner. (If working with a partner, the partnership should be clearly indicated in the submission notes.)

In the past, I have given ML assignments involving "traditional" ML projects like building up a small language parser or other heavily "data-structures" oriented tasks. Since we effectively already did that in the first 1/3rd of the course, I wanted to make this one a little more "fun". To that end, implement a simple one or two player card game in SML/AliceML* and create a simple computer opponent to play against.

* The use of another language is permissible only with instructor permission. The point is to do this in a functional language in a functional style. Other languages that I would consider allowing would be Haskell, Ocaml, F#, or even Scheme. Of course, I have little more than a superficial knowledge of some of those languages, you would be mostly on your own.

Also note: Feel free to use ML's "Basis Functions" (the standard library) where appropriate. The only things that I DO NOT want you to use are the Array functions or References; this is simply because the goal of this project is to teach "Functional Programming". ML, while primarily a functional language, it is not technically a "pure functional language", as it offers both Functional and Imperative constructs. Arrays and References are examples of those imperative constructs.

Requirements:

The program should represent cards as values of specific types and the deck as a list of those cards.
The computer should be able to ÎéÎíshuffleÎéÎí and deal "random" cards to the players.
Yes... this is a bit "non-functional" but not that hard either.
The player should be able to indicate their desired action on a given turn (e.g., Hit or Stay in Blackjack, which cards to discard in poker, etc.)
The computer opponent should respond and play appropriately.
(The computer AI does not necessarily need be "good", it should just play legally).
The game should continue though at least one complete "hand" of the game.
 
 NOTE: For those with moral oppositions to gambling, you don't need to think of this as anything other than an implementation of a basic strategy game.
 No "betting" or "gambling" is necessary or encouraged.
 (Personally, I'm not morally "opposed" to gambling per-se, I am just of the philosophy that most gambling is simply a tax on people who are bad at math.)
 Some game examples that should not be too difficult:

 Casino Type
 Blackjack
 You needn't worry about "splits" and "double downs"... unless you really want to.
 This is probably the easiest one to do!
 Draw Poker
 A simple "3-card" draw variant would be sufficient.
 Others
 Solitaire
 There are numerous simple variations, but "Klondike" would be manageable.
 Despite the lack of a "computer opponent", solitaire's rule complexity may make this one of the more difficult options.
 Due Dates

 The due date(s) will work work a little differently for this project. To better simulate the structure of many "real world projects" (especially government contract projects) there will be RFI (Request For Information) cutoff and a Deliverable cutoff.

 RFI: Midnight, April 18th
 No further project specification questions will answered after this time.
 Deliverable: Start of class, April 23rdth.
 All Source code must be submitted to Blackboard.
 Submit

 ML Source file(s) for your solution
 Should be reasonably well commented and free of Syntax errors.
 Brief description or any relevant notes for testing your program.
 NOTE: The program should run when "stated"... the user should not need to manually invoke a function to get it going.
