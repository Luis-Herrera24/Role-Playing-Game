# RPG Game Project

## Overview
This project is a semester-long development of an RPG game in Java, where the team created various character classes with specific abilities. The project was built gradually, with each part adding new features and fixing existing issues.

## Project Structure
The project is divided into three main parts:

### Part 1
- **Luis Herrera (lah136)**:  
  Filled in the `constructPlayerFromInput` method, added missing instance variables, and created getter methods in the `PlayerData` file.
- **Ray Rojas (xvc3)**:  
  Filled out the `constructPlayerFromElement` method and performed general troubleshooting.
- **Joseph Sheraden (jas759)**:  
  Wrote setter methods for the `PlayerData` class, added necessary comments, and determined the correct file paths for data access.
- **John Yamamoto (jmy40)**:  
  Called the `constructPlayerFromInput` constructor, passed the string from `main`, and invoked the `addToXML` constructor. Added a player to the playlist in the `populatePlayerList`.

### Part 2
- **Luis Herrera (lah136)**:  
  Constructed the `BaseCharacter` class and the `Abilities` interface. Assisted with JavaDoc and troubleshooting.
- **Ray Rojas (xvc3)**:  
  Added `try/catch` blocks for error handling.
- **Joseph Sheraden (jas759)**:  
  Wrote the `MagicCharacter` class and added comments in various places.
- **John Yamamoto (jmy40)**:  
  Created the `FireBallScroll` class that implements `Abilities`.

### Part 3
- **Luis Herrera (lah136)**:  
  Transferred files from Project 2 into this new project. Fixed errors from the previous project, including handling incorrect arguments. Created the `BardCharacter.java` class and worked on parts of the GUI, including the dropdown box showing player names and win rates.
- **Ray Rojas (xvc3)**:  
  Created the GUI, including the frame, buttons, and event listener actions.
- **Joseph Sheraden-Urrutia (jas759)**:  
  Worked on the ability classes, particularly `LuteMusic`, and cleaned up the code for better readability. Wrote and formatted documentation for all character and ability classes, as well as the `GraphicalUserInterface` class. Wrote release notes and generated the Javadoc.
- **John Yamamoto (jmy40)**:  
  Created the `FighterCharacter.java` class, which extends `BaseCharacter`, set hit points to 150, and armor to heavy. Created the `ShieldDefense.java` class that implements `Abilities` and added the new field `failureGraphic`.

## Release Notes
### Known Bugs
- The `FireballScroll` ability occasionally casts without being clicked on.
- Win rate only appears when the user clicks on the dropdown menu.
- Buttons appear in color for Windows users, but not for Mac users.
