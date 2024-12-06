//            ABOUT GAME             //     

1. All game Assets were created by Ash Thompson in Procreate.




//          GAME OBJECTIVE           //

1. Avoid Fire Ants, the game timer reduces by 3 seconds and the score by 3 points.

2. Eat as many Flies and Moths as you can to increase your score.

3. A Moth adds 5 points to your score and adds 3 seconds to your time.

4. A Moth will move their position every 2 seconds.

5. A Moth increases the frog's speed by 1.5 for 3 seconds.

6. Flies add 3 points to your score.



//            CHANGE LOG             //

oct 7 
- added highscore class to handle username and score
- highscore tracking for top 10 high scores via text file
- added username input to initial content dialog box
- added speed property to GamePiece in order to increase/decrease speed based on collision with certain edibles


Oct 8
- added music capability
- added increased speed functionality when frog collides with a moth
- added inverted colouring to frog img when speed is increased

Oct 12
- created loop for if a user fails to input a username
- added border to game grid and adjusted bounds for edibles and frog

Oct 15
- moved spawn collision detection to game piece class
- move RectsIntersect method to a newly created Utility class
- styled invalid username error message
- updated rules
- cleaned up code and added more explanatory comments
- added constraint to username length

Oct 16
- fixed error in score assingment for fireant
- fixed issue with spawn collision check / geting stuck in inifinite loop
- moved event registration for key down from page load to start game method
- added a background image to game grid, removed border and adjusted collison code 
- adjusted colours to background grids