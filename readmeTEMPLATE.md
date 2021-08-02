## Readme chingu solo project Template

# Title 
<describe the project>

<image screenshot or gif of project>


## Overview

<Give a general goal of building the solo project>
<info: The Solo Project allows new Chingus to find out which Tier they best fit in, and build a project from start to finish to ensure they are ready for the team Voyage project.
The solo projects are organized by Tier and requires skills that match the tier that best suits your current skill level. Don't worry if you find that you have selected the wrong tier - you can change your tier at any time.>
<include any references that might be interesting or useful>
<Example:   A small history of turned based RPGs and the evolution of Role Playing games in the 21st century>

## Instructions

<allowed frameworks and libraries>
<link to the Chingu solo project docs??>


## Specifications

<example>
### Documentation/ReadME

[] Explain the purpose of the game, this can be in story format
[] Technical documentation: Explain the game play and what features do
[] solo projects must have a robust Readme, this is helpful for code reviews and practicing good documentation habits.

### Landing page /index or home page:

[] create the landing page to reflect a consistent theme that will carry throughout the application
[] create a play button that leads to the game play on this page 
[] With either single page navigation or routing navigation, this button should lead to the gameplay 

### Game design

[] Create a 'character selection' page before the battle simulator that allows the user to select thier champion.
[] The choice of character should be reflected in the battle simulation by character image at least. 
[] There only has to be one enemy for the battle. Reflect it's name in the simulation, and have an image to represent it.
[] During player turn they should have an 'attack' and a 'defend' button. Classic RPGs usually had the options to flee from battle,
but this is not required as you need to only make one battle simulation between player and monster.
[] You can create your own assets/images or use the ones provided in the assets folder <here:link to assets in repo> 

### Turn-based Battle simulation. UI/UX:

[] Users should be able use all interactive components in mobile and on desktop. See <link to description of 'responsive'>
[] Users should be able to see information displayed in text format somewhere on the screen.
[] information should be updated on both the players turn and the enemies turn. 
[] When users click an action, the action should be carried out and results shown in the game play 
[] Refreshing page does not have to store data and it's ok for it to be reloaded from source 
[] clicking anything other than the action buttons in the player menu should not change the game
[] player actions should not be 'clickable' while the 'enemy' is taking its turn. 
[] hit points or health of the player and the enemy should be visible at all times during the battle. 
[] attack should lower the 'hit points' (never 0) of an enemy by some random, or semi-randomly generated pattern
[] defend should lower the enemies attack in some random/semi-random pattern, never 0. 
[] Enemy attacks should take some life points, or hit points from the player, never 0.
[] When the player or enemy attacks the amount of damge done should be reflected in the 'hit points' or 'health' displayed in game.
[] If the enemies hit points are reduced to at below zero, a 'you win' message should be displayed with a 'play again' link to landing page.
[] if the players hit points are reduced to at or below zero, 'you lose' with redirect to home page in the 'play again'
[] Players attack and defend options should not propegate click events during the enemies turn.

###  Stretch goals   NOT REQUIRED

**These are not required for a complete submission.**
[] Display a description of characters in the character selection screen
[] Display the 'stats' for character choices in the character selection screen
[] Upon winning show a 'mock' example of character gaining gold, and experience from the battle
   In classic RPGs this what a simple text box display that told the player how much gold and experience they had gained from a successful battle. 
[] Anything else you'd like to jazz up the game.  Rememeber to make sure all the Specifications are met, and have fun.


<any additional information or links that can be useful to the chingu>
