# blackjack
pyskulptor black jack
Project Overview:
This document specifies the requirements met to improve an existing web interface provided with a simple game of Blackjack. 
Using CodeSkulptor.3 (https://py3.codeskulptor.org)

How to Play:
The goal of blackjack is to beat the dealer without going over 21.
The dealer starts with two cards – one faced upwards and the other faced down.
Each player starts with two cards – both faced upwards.
Each card is worth the number on that card – an Ace can be worth 1 or 11, picture cards are worth 10. 
The aim is to get the closest to 21.
“Hit” asks for another card.
“Stand” Holds your total and ends your turn.
After you turn, the dealer will ‘hit’ until they get 17 or higher.
Whoever gets closer to 21 wins. 
If either player goes over 21, they are busted and lose the round.

Operating Instructions:
Game Screen
“Hit” gets another card, this is added to your total.
“Stand” means the player doesn’t accept any more cards and their turn is over, then it is the dealer’s turn, and you can see who won the round.
“Deal” starts a new round; both the dealer and player get dealt new cards.
“Menu” (also denoted by the three lines on the alternative background game screen) takes you to the Menu page. 
“Start Over” starts a new game, clearing both the dealer and player’s score back to zero. 
The “Hand Total”: is not a button but it helps the user know the sum of their cards.
The timer is also visible on the screen to show the player how long they have left to decide. The player gets 120 seconds to complete their round, once the winner has been recorded, the timer restarts. When the player has 10 seconds left, the timer goes red to indicate they’re running out of time. 

Menu Page
“Settings” button takes you to the settings page. Where you can click the buttons for “Volume up” – increase the sound of the effects, “Volume down” – decrease the sound, or “mute volume” – Remove the sound. The font can be increased or decreased by pressing “Increase Font” or ‘Decrease Font’ respectively. There is an option for “Audio Assist On/Off” to turn on voice overs, which allows individuals who are hard of sight to play the game. “Back” takes you back to the Menu page.
“Switch layout” changes the background and layout of the GUI to an alternative ‘Art Deco’ inspired design. 
“Scatter Plot” shows the statistics for number of wins and total games played. 
“Back” takes you back to the GUI Game Screen page.

The Control Panel
Also has the buttons for Audio: “Volume Up”, “Volume Down”, “Audio Assist On/Off” so the player can change the settings while playing without going to the Menu and Settings page. 
Display: “Toggle Layout”, “Increase Font”, “Decrease Font” and the option to change the background colour of the simple layout between blue and green. 
Statistics: “Scatter Plot” gives a visual interpretation of the Number of Wins vs Number of Games.
“Start Over” is also found on the control panel (as well as the GUI screen). This re-starts the game, all scores go back to zero, and new cards are dealt. 
“Quit” ends the game and closes the pop-up window. 
The Control Panel also states the shortcut keys; Hit = F, Stand = J, Deal = Space. 

User Accessibility:
Visual Accessibility
Large buttons found on the GUI screen and the side menu. The buttons regarding to playing the game are on the GUI screen to make it clear which to press while playing. Once the player has chosen to ‘Stand’ the buttons for Hit and Stand disappear making it clear the player must click “Deal” to play the next round. 
Two background options give the adaptability to fit the user’s preference, a classic Blackjack layout which is simpler, as well as an ‘Art Deco’ inspired background.
The option to increase or decrease the text size to aid the visually impaired. 
The total sum for the dealer’s and player’s cards to help speed up the game and make it easier for the user.
A button in the control panel to change the colour of the basic Blackjack theme background.
Hearing Accessibility
Game sounds which can be raised or lowered to aid the hard of hearing. Can also be used by visually impaired people as a hint to what stage they are at in the game, and to help with whether they win or lose the round.
Voice overs can be turned on in Settings by clicking the “Audio Assist On/Off”, these greatly help the visually impaired and ensure they can play the game.

Mobility Accessibility
Keypad controls for those who struggle with moving a move to a small button or hold it over the button for the period of time to press it. F = Hit, J = Stand, Space = Deal. The up and down buttons can also be used to increase/ decrease the volume. 
Buttons on the GUI screen so they are close to what they are representing to help the user understand what each button means, also so they don’t have to move the mouse far. As well as the use of buttons in the control panel to give a suitable player opportunity to everyone. 
The use of the mouse or track pad to give options to suit everyone. Easily able to press the buttons with a single click.

Prevention of Cheating:
The timer stops the player after 120 seconds to stop them from researching and cheating to get help with the answer. The timer is also visible on the GUI screen, so the player knows how long they’ve got to complete each round. If the user were to change screens during their play, to the Menu or other game background, the timer continues so they can’t pause it and research how to win. Once the time is up the dealer gets the point for that round and the timer starts again. 
If the "Deal" button is pressed at the start of a round, a point of 1 is added to the dealer’s score, as if the player were to forfeit the round. This ensures the player can’t cheat by clicking it repeatedly until they get Blackjack or cards they want to start the round with. The “Deal” button must however be pressed at the end of each round to deal both the dealer and player new cards – this doesn’t increase the dealer’s score. 

File list:
UML use-case diagram
Python GUI
README plain text
