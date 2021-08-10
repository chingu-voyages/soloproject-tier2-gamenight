# soloproject-tier2-gamenight
Chingu Solo Project - Tier 2 - Chingu Game Night

## Why make a solo-project?

The Solo Project allows new Chingus to find out which Tier they best fit in, and build a project from start to finish to ensure they are ready for the team Voyage project.
The solo projects are organized by Tier and requires skills that match the tier that best suits your current skill level. Don't worry if you find that you have selected the wrong tier - you can change your tier at any time.

## Goal: Make a turn based RPG

There are many forms a 'Role playing game' can take.  For this adventure, the classic hero story, with a 'turn based battle' element will be the focus. 

Older generation video games did not have fancy graphic engines to help facilitate battle between the heros and the villians.  Turn based battles have evolved over the years, but some of the ancient gamers of yore still have a special place in thier hearts for the turn based battle simulation. 

If you'd like to look up what kind of games used this method of story, leveling and battling, the most popular and longest running
franchise to date might be one you are familiar with. It's name is Final Fantasy.   

For this project you don't need to worry about creating the story, leveling or menu/inventory system. The goal is to recreate a rpg type turn based battle that the user can interact with and accomplish a win, or a lose depending on the outcome of the battle. 

## Tech Stacks

You can use any tech stack you choose. Frameworks and libraries are allowed. 

Because graphics, and sprite/image creation is not everyones favorite hobby, there are sprites you can use in the assets folder of this repo.
Feel free to create your own, but remember the goal is to create the functionality and user interface. 
Don't let creating the image assets eat up your time. If you have a different resource for your image assets you'd like to use, 
you are free to do so.

About Turn based battle: 

Turn based battle allows for the player to choose thier action against an enemy before the battle proceeds. 
The battle usually begins with the player being able to choose thier first action.  After the player has chosen, the actions should be 
carried out.  This would be reducing the enemies hit points and displaying a message to the player.
After the players turn has been carried out it is time for the enemy to act. 
Enemys actions in early rpg games tended to be static for most fights. For example, the batty bat in the assets folder only attacks and 
deals damage to the players character. The enemies actions are also displayed on the screen for players to read.  Once the enemies actions are complete it is once again the players turn to choose what they would like to do. 

## Functionality
 

There needs to be at least three different rendered pages(or components) that appear as a user progresses through the game. 
Every page should be responsive, and fit correctly into a mobile sized screen, as well as desktop.

1) A home page, or start screen 
2) A selection page, where a user selects the champion they would like to enter battle with
3) The battle simulation screen

   >a)battle simulation should display the enemy or monster image.

   >b)battle simulation should also display the player image.
 
   >c)Enemy and player health or hitpoints should be displayed at all times.
   
   >d) information about the results of the users actions, and enemy actions should be displayed during the length of the battle.
   
   >e) text results can fade away or be replaced, but make sure the user has time to see them.
   
4) The results of the battle.  This can be displayed over the battle simulation. 

## User Interface

[] User clicks a button or link that leads them to the selection page(component). 

[] In the selection page the user has at least three different characters to choose from. 

[] Along with displaying a picture of the character, an informative text should appear and change to explain
to the user what the characters special traits, abilities or skills are. 

[] When the character is selected from the selection page, the user should be sent to the battle page(or component).

[] In the battle page the user's turn should be first .

[] The users character should have at least two abilities it can select against the enemy.

>> for example:  fight and defend 

[] Once a user has chosen an action, the results of this action should be carried out on the battle screen/page

>> Hitpoints or health of the player and enemy should be impacted by both the players turn and the enemies turn
>> text should display saying what the player chose to do, and what damage the player has inflicted
>> on the enemies turn, the action of the enemy should be displayed and the damage the player recieves displayed
>> Remember that the hit-points/health should reflect the damage done to both the player and the enemy at the end of the turn.

[]  A battle is won once the enemies hit points have been reduced to at or below 0. 

[]  A battle is lost once the players hit points have been reduced to at or below 0.

>> Remeber to make it possible for the player to lose a battle, for example by defending multiple times, so that evaluators can see lost battle results as well as the win battle results. 

## Special Notes
[] Data does not have to be stored between pages. 

[] Refreshing can lead to the home (start game) page, or the same page the user is currently on.

[] When creating the battle in code, using a random number within the scope of the player and enemies hit points is adventageous.


### Stretch (optional) goals
[] Give each character a set of 'stats' that influence how the battle actions effect the outcome.

[] Give the enemy and player dialog to say during thier turns in battle. 

[] Give a visual indication of the player in the battle page to show that they are 'defending' or 'fighting'

Let the adventure begin! 
