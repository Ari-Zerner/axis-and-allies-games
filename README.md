Branches should follow a tree structure where the initial commit branches into
the different game types, each of which should have one commit with the save
file for a new game, then branch into individual games. The branches for
individual games should be named as follows:
    "allies-player-vs-axis-player-n"
where allies-player and axis-player are the first and last names of the
players, and n is the sequence number of this exact player setup. e.g. the
second game where Foo Bar plays Allies and Baz Qux plays Axis would be called
"foo-bar-vs-baz-qux-2".

Games should have one commit for each turn, containing the save file after that
turn. The messages for turn commits should be the turn names according to the
convention laid out here:
    https://boardgamegeek.com/thread/782025/axis-and-allies-abbreviations-and-acronyms
e.g. the commit after America's third turn should have the message "A3". There
should be one final commit with the message "Outcome" that updates Outcome.txt
with the outcome of the game.
