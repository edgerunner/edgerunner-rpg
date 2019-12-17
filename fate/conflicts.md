# Conflicts

Whenever the push comes to shove, and a simple task or a contest isn’t enough to satisfy everyone, it is time to dive into a _conflict_. A conflict is a systematic and verbose method to resolve a complicated situation and unlike some other games you may know, conflicts in edgerunner are _not limited to combat_ situations, although it is the preferred method for that.

Conflicts are verbose, and take some time to resolve. Before breaking out into a conflict, always consider resolving the situation with a simpler method. The best conflicts are ones that generate lots of story details, without dragging out the outcome. If a conflict looks like it is going to consist of mostly the same moves repeated over and over, reduce it into a [contest](resolution.md#contests) and be done with it.

A conflict has a number of specific features

* It consists of a sequence of _exchanges_, periods of time where everyone involved gets to take one action.
* It is played on a _map_ that sets the scene. This map can represent a real location, or it can represent an abstract space such as moods, social circles or network nodes. The map consists of discrete _zones_, with _borders_ between them.
* Every action in a conflict must conform to one of these:
  * A _move_ action to move something between zones on the map
  * An _attack_ to take out an opponent
  * A _defense_ to modify a stress threshold
  * A _maneuver_ to place an aspect on something
  * A _recovery_ to reduce hits on a stress track
  * A _resist_ action to prevent one of the above from happening
  * A _continue_ action to keep on doing the same thing
  * A very simple action that does not require a test or contest
* It ends when one side either _concedes_ or is _taken out_

Other than that, what you can represent with a conflict setup is quite flexible. A firefight or brawl is an obvious candidate, but a heated debate, a hacking attempt, a car race or a corporate hostile takeover action can very well be played as a conflict.

Conflicts may seem mechanical, but do not skip the storytelling. Every action made in a conflict should generate a story detail. Remember, that’s what this game is all about.

### Exchanges

{% hint style="warning" %}
Things happen step by step in a conflict. An exchange consists of a time period where _everyone gets to act once_.
{% endhint %}

The duration of an exchange is not set in stone but it is a good idea, for the sake of consistency, to pick a duration from the time track. “3.3 seconds” or “2 weeks” is too rigid. “a few seconds” and “a couple of weeks” are better, as the implied flexibility of time reduces debate on what can and cannot be done in one exchange.

The characters take their actions one by one. The question of who goes first is called the _initiative_. There are multiple methods for determining initiative, but the one we recommend is called social initiative.

Social initiative is simple: _Whoever wants to go first, goes first._ Of course this requires some arbitration. Designate a player to be the _caller_. The caller should preferably be someone not involved in the conflict, otherwise the referee can become or appoint the caller. The caller is supposed to keep track of who has acted and who will act next.

At the beginning of an exchange, and after every action, the caller asks “Who’s next?”. Whoever responds first gets to act. If multiple players want to act, the caller runs an auction on how many shifts the players are willing to commit for acting first. The highest bidder gets to act but must subtract his bid from his roll.

### The map

The map is probably the most important feature in a conflict. It portrays the environment and provides details for all kinds of opportunities and threats.

A map consists of zones, which are of variable size, geometry, and description. A zone should be defined as any space\(physical or abstract\) that is discrete from others. The basic rule in considering if a feature on the map warrants its own zone is _if it would make a diffrence to be there or not, then it is a zone_. Considering an indoor map, a room with walls and a door is definitely a zone, but a huge room may be split up into multiple zones, because it would matter which end of the room you are in. In an outdoor map with huge spaces, that whole building may be represented as a single zone because all that matters is if you are inside the building or not.

Zones are connected to each other with borders, through which movement may be possible. All borders have a _pass value_ which defaults to 1, and that pass value represents the cost of moving through that border. A border may represent any kind of persistent obstacle, or just inherent difficulty in passing from one zone to the other. For example, a low wall may be a border with a pass value of 2, or a border between two crowded zones may have a pass value of 3 because of the difficulty of moving through the crowd. Things like firewalls defending computers connected to the net, or the red tape around scoring an interview with an important government official may also be represented as borders with higher pass values.

It is possible for a border to have more than one pass value for different conditions. For example, the wall between two rooms, with a door on it may be; 1 to go through the open door, 2 more to open or close the door, 4 to break the door or 7 to break through the wall. A border on a slope may be 1 when going downhill and 3 uphill.

### Actions

Conflict actions are different from tests and contests that they are limited to interacting with things on the map only. Anything beyond this principle is out of the scope of that conflict, and should be resolved afterwards.

{% hint style="warning" %}
Every character on the map can take _one action per exchange_. After taking your action, you have to wait until the next exchange to do anything else.
{% endhint %}

After a player declares his character’s action but before he rolls the dice, the caller calls for compels. Compels work the same way as described in [using aspects and fate points ](aspects-and-fate-points.md)but the result of a compel is more constrained in a conflict. _A successful compel causes the compelled character to skip his turn_, for whatever reason that fits the compelled aspect.

#### Move

A move action represents the concentrated effort to cover distance on the map. The character rolls the appropriate skill vs. 0, and the number of shifts is the limit on the total pass values of borders he can go through. If he rolls badly and gets a negative result, he may get spin, which can be used against him later. He can still use his free move though.

If shifts from the movement roll are not enough to overcome a border value, the character cannot move through that border. He may attempt invoke aspects or take stress and consequences to boost his movement.

{% hint style="success" %}
 Gatto is trying to make it to the other side of the crowded warehouse in order to give his opponent a solid punch in the face. The warehouse is one big rectangular space, large enough to consist of three square zones side by side. The warehouse is not very well organized, and the aisles between racks and containers resemble a labyrinth. Therefore the borders between zones in the warehouse have a pass value of 3 each.

That requires 6 shifts to make it to the other end in one exchange. Gatto manages 2 shifts with his Athletics skill 3 of and and a roll of ⊞⊡⊟⊟. Not even enough to move a single zone! 

 Jon considers marking stress and/or consequences to make up for the more shifts he needs to go all the way, but decides to save his resources for the upcoming scuffle.
{% endhint %}

**Move another**

You may want to force a resisting target to move on the map. Driving the enemy out of Hill 319 and persuading someone on a map of opinions are examples of moving another entity on the map.

When determining range to the target, use the target’s starting zone.

The target’s player has the option of resisting the move, stealing shifts from the roll.

{% hint style="success" %}
Jade is online as her alternate identity; Nephrite. She is trying to get rid of the IC daemon that is giving her a hard time. This iceboy is very effective in keeping her from reaching her goal, the research data she was hired to “liberate”. Since her attacks seem to be totally worthless against this hardened pile of binary code, she chooses to go for another tactic.

Nephrite decides to move it out of the way and uses her Deception of 4 against the daemon’s Netrunning of 2. After dice are rolled, she gets 4 shifts. Great. She pushes the daemon four zones out, by tricking it to believe that it is defending the wrong spot. This will give her enough time to make a dash for the data she’s after.
{% endhint %}

Unless it is a map of metaphorical space, _factions don’t move_ on the map. Instead, they [deploy](http://edgerunner.merttorun.com/the-world/factions/playing#deploy-action) resources on the map.

#### Attack

An attack is an attempt to _take out_ an opponent in the conflict. An attack can take any form that is reasonable in the context of the conflict. Attempts to shoot, distract, tackle, frighten, persuade or any other thing that would force him to give up on the conflict are considered attacks.

Any shifts from the attack roll are applied as stress against the appropriate stress track of the target. It is assumed that the _target always resists an attack_ action. Not resisting an attack always ends up in being taken out, which is quite undesirable.

The mode of attack must make sense when the skill used and range to target is considered. You simply can’t punch a guy with two rooms in between, but assuming conditions are right, you may taunt and scare him.

**Inanimate targets**

Not only characters are the targets of attacks. Anything that resists anyone can be a target of an attack. For example, you can attack the integrity track of the stubborn lock on the gate with your electronics skill in order to bypass it.

It may also be possible to attack some kinds of borders on the map. If the attacker takes out a border, he can then redefine the border and its pass values, within reason. The border’s stress threshold is assigned by the referee unless preemptively declared by a player.

{% hint style="info" %}
[Complex devices ](../the-world/technology/complex.md)may actively defend themselves with an appropriate capability.
{% endhint %}

#### Defense

A defense is the active use of a skill to protect yourself\(or something else\) from stress. You may use an appropriate skill to replace the stress threshold on a stress track on your character or on another target.

{% hint style="info" %}
_The number of shifts you get from your roll determines the new stress threshold of the target stress track._ You must continue your action for this new stress threshold to remain in effect. It reverts to its original value once you take another action. It also reverts if the target moves.
{% endhint %}

If the stress threshold later reverts to a level where there remain marked boxes higher than the threshold, nothing happens. The stress threshold matters only at the moment stress is received. The boxes above the stress threshold remain as they were, to be considered if the threshold is raised with a defend action again.

{% hint style="warning" %}
Don’t forget that the range to your target is subtracted from your shifts.
{% endhint %}

#### Maneuver

The [maneuver](http://edgerunner.merttorun.com/fate/creating-aspects) is simply put, an action taken to place an aspect on something. Valid targets for maneuvers in a conflict include zones and borders on the map, any equipment used or lying around, and any of the characters involved.

The target number for a maneuver is zero. The aspect is considered placed with zero shifts. If a resisting target wants to block the aspect completely, they must reduce the roll to at most _-1 shifts_.

Seems easy, but with zero shifts, you just place the aspect but must use fate points to invoke it later. One shift on the roll buys you a free invoke to use in the conflict. Two more shifts buys a second free invoke, three more buys a third.

The number of free invokes you can get is also the number of stress boxes this new aspect has, for the purposes of constituting a target if someone else attempts to get rid of it later.

You should remove such an aspect instantly _if it ceases to make sense_. This doesn’t mean the you can instantly remove an aspect if your character is attempting to get rid of it. That would be the subject of an attack action with the aspect as its target. It only means that you should remove it if the description of the aspect becomes meaningless because of the things that happened after the aspect was created. This is especially true if the aspect describes a situation that requires the active participation of a character, and that character is no longer capable of participating. When in doubt, use table consensus.

Many preemptive defensive moves can be emulated with aspects. Want to do nothing but take cover? Use a maneuver to place `Dug in` on yourself, and tag it to boost your defense roll later. Want to keep a net node secure? Place an aspect; `Icewall` on the node, use it to compel anyone trying to enter. Want to protect your girlfriend’s peace of mind? Maneuver to place `"Let me handle this, baby"` on her and use it to give a hard time to anyone who approaches her.

#### Recovery

Recovery is an attempt to clear up a stress track in anticipation of more damage. Anybody may attempt to clear the stress on anybody else but both of them must use their action, ie. act together.

The shifts on the roll are used to clear stress track boxes. _You need a number of shifts equal to the box number to clear a single box_. You may clear any number of boxes anywhere on the track as long as you have enough shifts.

{% hint style="danger" %}
You cannot clear a box unless you get enough shifts. This makes higher level boxes very hard to clear. Invoke aspects to get enough shifts to clear them, or don’t get hit in the first place.
{% endhint %}

Recovery does not necessarily represent “healing”. Anything that gives any kind of relief or breathing room to a character may be represented as a recovery action. Supporting a friend’s lie may be a recovery action if she’s being grilled. Covering fire may give the other squad a moment to catch their breath, recovering their stress boxes.

{% hint style="danger" %}
_Only stress tracks may be cleared in a conflict_. Any consequences remain regardless of how long an exchange may take.
{% endhint %}

#### Continue

This is a special type of action that lets you keep the investment you made for a previous action.

In Edgerunner, you cannot retry an action. Any retries your character makes are rolled into the story generated by the single roll you make. But in conflicts that consist of exchanges with a limited time frame, this does not work. For this purpose, there is this “continue” action that allows you to build on the action you chose in the previous exchange.

Remember that the core parameters of a conflict action are the _skill_, the _action_, and the _target_. If all of these are the same as they were in the previous exchange, _you cannot roll again_. Instead, you must take a continue action.

{% hint style="info" %}
With a continue action, you _don’t roll the dice_, but _you get the same number of shifts you got for the previous exchange_, including any bonuses gained from aspect invocations. You may spend these shifts as allowed in the previous action.
{% endhint %}

You may still opt to invoke more aspects and boost your roll, except the ones you had already used previously. You may also use an invocation to re-roll the dice from the previous exchange. \(It’s a good idea to keep your dice untouched until it is your turn again. It makes keeping track much easier\)

{% hint style="danger" %}
Any [upgrade effects](../characters/upgrades.md#upgrade-effects) are already rolled in from the previous exchange, so you do not add them again, but that means you do not receive any additional humanity stress either.
{% endhint %}

#### Resist

Resisting is the only thing you can do if it isn’t your turn. It is the only immediate response you can give _if you are the target_ of an action.

You do not roll when resisting. Instead, you _take stress and/or a number of consequences, and remove shifts from the ongoing action_. You may choose to drive the shift total to zero or less, completely stopping the action, or you may just kill some of its shifts to reduce its effectiveness. You may also invoke aspects to reduce the roll by 2 or force a re-roll.

Except when resisting direct attacks, you determine the type of stress you take from a resist action. Of course, your decision must be backed up by your story. Better come up with an interesting explanation of how your Reputation gets bruised by bullets or the table may override your decision.

You must be the target of the action in order to resist it. You cannot resist actions directed at other targets. Try to “defend” them so that they can resist more. Get your defenses up early in a conflict, so that you can resist more.

#### Simple actions

If an action is simple enough not to warrant a roll, and it can fit in the time frame of an exchange, then it can be done in a conflict. Anything that involves a roll however, must be modeled as one of the actions above.

#### Long actions

If you are trying to do something that would take longer than an exchange, then model it as a _problem_ that has an aspect \(or two\) and a stress track that can be attacked using a skill.

The stress threshold of such a problem is determined based on the difference between the duration of an exchange and the time it would normally take with a mediocre roll. The difference as steps on the time track is stress threshold of the problem.

The problem can be “attacked” to solve it, and “defended” to keep it from being solved. A “recover” action can be used to revert it to its initial state, and aspects can be placed on it with a maneuver. If it makes sense, it may even be moved on the map.

A problem is solved if it is taken out. Whatever the original intent was, consider it accomplished.

### Game over

There are two distinct ways that conflicts end in Edgerunner. If every actor on one side of the conflict is _taken out_, the conflict ends in a messy manner. To prevent that, the losing side can offer a _concession_, a story acceptable to all sides, that marks the end of the conflict.

#### Taken out

If a character\(or any other thing\) receives stress higher than his _threshold_ on any of its stress tracks, he is considered taken out. This is an important thing. _The player loses his control over the destiny of a character who is taken out._ The opponent now determines what happens to the character, in accordance with the last action that took him out. This is a powerful ability. The opponent can narrate anything that makes sense in the context. The character is almost completely at the opponent’s mercy.

{% hint style="success" %}
Gatto got a real bad roll for his defense, and his opponent Hargan took advantage of this by invoking Gatto’s `Only if this @#! gun fired once in a while` aspect to deal a whopping 8 points of stress to his cool track. This is something that Gatto cannot handle with all the previous stress he suffered. Gatto is taken out.Gatto has lost his cool, and Gatto’s player, Jon, has lost his right to say what happens to Gatto. That right now belongs to William, Hargan’s player.William considers the fact that Hargan and Gatto both used their Firearms skills for offense and defense respectively, and that he invoked Gatto’s aspect, he comes up with this story:

> While Gatto was trying to keep Hargan from shooting at him by some heavy return fire, he suddenly realized that he had a bad bullet in the chamber. With his gun jammed, he hesitated just long enough for Hargan to put two bullets in his right arm, dropping him instantly due to shock. Gatto is reduced to a bleeding pile of meat on the ground, in too much pain to move or do anything meaningful except maybe call for help.

Jon, Gatto’s player can do nothing but accept the sad fact about his character. He shouldn’t have let this happen.
{% endhint %}

{% hint style="danger" %}
Conflicts are the highest form of dispute resolution in Edgerunner. If you enter a conflict and get taken out, you have to suck it. There is no appeal for a plausible taken-out result.
{% endhint %}

#### Concessions

There is something you can do if you are stuck in a losing battle. You can offer a concession. A concession is a story that ends the conflict, possibly one that will be advantageous to your opponent, but not as detrimental for you as actually being taken out. _If your opponent accepts your concession, the conflict ends with the story you just offered._

{% hint style="success" %}
Now that Gatto is down, Sandra, Jade’s player realizes that Jade doesn’t stand a chance against Hargan alone. She offers a concession:

> Jade breaks her data uplink and while firing her SMG frantically, she scuttles Gatto out of there. She fails to upload the data they came for.

William sees that this story is good enough for him, as Hargan has successfully kept Gatto and Jade from stealing the data, and continuing the fight may still result in Hargan getting taken out. He accepts the concession, and the conflict ends.
{% endhint %}

It is good to discuss and modify the offered story a little, but if it turns into a haggling slugfest, stop and continue the conflict. Just as in a game of Go, a conflict ends when everybody agrees that it ends.

