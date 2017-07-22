Commit format: Branches should follow a tree structure where the initial commit
branches into the different game types, each of which should have one commit
with the save file for a new game, then branch into individual games. The
branches for individual games should have one commit for each turn, containing
the save file after that turn. The messages for turn commits should be the turn
names according to the convention laid out here:
https://boardgamegeek.com/thread/782025/axis-and-allies-abbreviations-and-acronyms
e.g. the commit after America's third turn should have the message "A3"
