Most cards follow the same general structure, however, [[Mech]] cards do not. Their structure will be noted later in this section. 

## Regular Cards
![C:\Users\Chris\source\ruby\MechaZooCardCreator\out\mechazoo-base-set\example-card.png|300](file:///c%3A/Users/Chris/source/ruby/MechaZooCardCreator/out/mechazoo-base-set/example-card.png)
(figure a: an example card.)
### A: Scrap to play
This field tells you how much scrap it costs to play this card during the build phase.
Cards that don't cost scrap (e.g. action cards) will have a 0 in this field.
### B: Card Type
{Playtest} This field will have one of the following values:
* !: Action
* @: Part
* $: Crew
### C: Energy to Activate
This field tells you how much energy from your mech core this card costs to activate. 
### D: Durability
This field is sized to allow you to place a six-sided die (12mm, if you're buying replacements) on it to mark how much durability a part has. 
Cards that don't have durability (e.g. Crew and Actions) don't have this field at all.

### Typeline
This field contains the types of the card. Some examples of lines you may see here are:
* Scrapper - Energy Weapon: This is a weapon part that can only be attached to mechs with the "Scrapper" keyword, and when it attacks, it deals Energy damage, which is referenced by some card effects.
* Assistant: This is a special kind of crew card of which you can only have one in play at a time. If you play another crew card with the Assistant type, your existing assistant will betray you.
### Limit
This field is only relevant when playing in a tournament. During constructed tournament play, you cannot have more copies of a card with limit than its limit rating in your deck. 