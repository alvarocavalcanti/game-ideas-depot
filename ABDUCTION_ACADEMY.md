# ABDUCTION ACADEMY

## Key Thought

Well, the inspiration for this was Pixar's [Lifted](https://en.wikipedia.org/wiki/Lifted_(2006_film)), an animated short, in which a visibly inapt alien tries to abduct a sleeping human under.

(It's a great short, go watch it now!)

The idea here is to simply abduct the sleeping subject (sleeper), while avoiding waking them up, been spotted by awake bystanders and before the sunrise!

## Core Mechanics

So far there are two possibilities:

  1. Wherever the player touches the screen a tractor beam would be fired (along the Y-axis, anchored at the X coordinate of the touched point)
  2. A control panel on the bottom of the screen provides two clumsy tools. A dial/lever that would move the tractor cannon and a switch that would turn it on/off

Some experimentation needs to be done here, in order to test both possibilities. The goal is to make the abduction process a little clumsy (but not to extent of not being fun).

When a sleeper is hit by the tractor beam it starts lifting from the bed. When the beam moves sideways, it also drags the sleeper around, but slower (or at a capped speed). So the player has to keep it cool and drag fast, otherwise the sleeper would fall.

A sleeper should have a sleeping limit, which would be checked against bumps, drops or similar events (to be defined).

Some levels might have awake NPCs that cannot see the sleeper being abducted. That would force the player to hide the sleeper in order to avoid being spotted.

Finally, the player loses if dawnn breaks and the sleeper haven't been abducted.

The abduction takes place when the sleeper reaches the tractor cannon.

## Level Design

The most basic levels would introduce the player to the core mechanics while abductin cattle on a farm. The first level could have a sleeping Cow out in the open, the next one has a cow under a tree, etc.

The levels would go from farm fields, to farm houses, to city houses/apartments.

The awake NPCs should not have a visible field of view. If they're facing towards the tractor beam, they can see it.

## Art Direction

Nothing defined yet. Still it's easy to get influenced by Lift's art style. :)

## Prototypes

1. Abduction Proto With Flixel, by Alvaro Cavalcanti:
  - [Source-code](https://github.com/alvarocavalcanti/abduction-proto-flixel)
  - [Playable version](http://alvarocavalcanti.github.io/abduction-proto-flixel/game.html)

## Implemented Games

1. *Add here the games that implemented this concept*
