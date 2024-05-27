# Chronicles of War - Prototype - Technical Documentation

&nbsp;&nbsp;&nbsp;&nbsp; Board card game in a fantasy/medieval setting. Currently the game is in a prototype state.

Short demo video available at: https://youtu.be/g-7owNEO0VU

![Demo Image](/cow%20-%20screen.png)

#### Technologies

&nbsp;&nbsp;&nbsp;&nbsp; C#, Unity3D

## Features

### Current Targets

- Bot Battle
- Offline PvP Battle - single device only

*Use Case Examples*

- Lay card to battle
- Draw card to hand
- Move card on the battlefield
- Attack another card
- Use card skill
- Make cards react to events with their skills - effects

### Future Targets

- Online PvP Battle - across network, with random or specific players
- Deck Arrangement - arranging card decks for a specific gameplay style
- Cards Collecting - collecting cards after a battle

## Quality Attributes

##### Maintainability

&nbsp;&nbsp;&nbsp;&nbsp; Architecture should be arranged in such a way that in the future it will be easy to decouple domain logic to the separate server project enabling online multiplayer this way. 

##### Interaction

&nbsp;&nbsp;&nbsp;&nbsp; Since the gameplay is the biggest priority, visuals and interactive capabilities should be as minimalistic as possible, just enough to successfully finish a match. After most fundamental features implemented the detailed ux, graphics, animation, vfx, etc.. design should be carried out.


