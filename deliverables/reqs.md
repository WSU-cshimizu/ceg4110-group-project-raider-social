# Requirements Specification

## Tyler Wells
### User Story Developer
#### As a developer I want to develop the in-game toggle events(i.e score, start menu) to help ensure a straight and fun direction for a player to achieve goals and rewards so that they are obligated to be more 'engaged'.

 * 1.1 Implement Toggle Functionality of Score Display
   - The game shall provide a toggle feature that allows a player show and hide their score during gameplay. This feature will be provided as a hotkey option at the users disposal.

 * 1.2 Implement a Start Menu with Interactive Options
   - The game shall have a start menu on load up that allows a player to choose between options to start or quit game. It will be very easy to navigate and look appealing to the user. 

### User Story User
#### As a player, I want to be able to play the game with smooth representation of a competitive aspect so that I can beat other peoples high scores and enjoy the moment.

* 2.1 Real-Time Leaderboard Display
  - The game shall feature a real-time leaderboard that displays the top scores of players, letting users compete against one another.
    
* 2.2 Matchmaking System
  - In the future if we got far into our project, there shall be a matchmaking option for users to compete with one another.
    
## Hayden Troxell
### User Story Developer
#### As a developer, I want to develop the backend logic that will insure smooth collision detection, which will allow the player to enjoy the game and its enviorment without having any player model clipping issuses.

* 3.1 Accurate Collision Detection
   - The backend shall implement accurate collision detection that accounts collisions between the player model and the environment with no clipping issues.
     
 * 3.2 Continuous Collision Detection
   - The system shall provide continuous monitoring of in-game player movement and environmental interactions to ensure smooth and seemless gameplay.

### User Story User
#### As a player, I want to be able to use the basic game controls to traverse the world and try to beat my High-score while also not running into any bugs that will decrease my in-game immersion.

* 4.1 Fluid Game Controls
   - The game shall provide a set of responsive controls that allow players to navigate the game world seamlessly (ie: forward, backwards, left, right, jump)

 * 4.2 Stability and Bug-Free In-game Experience
   - The game shall ensure a stable and bug-free gameplay experience by minimizing faults that could disrupt player immersion and ruin the player experience.

## Dipesh Paneru
### User Story Developer
#### As a Developer, I want to implement feedback when the player performs certain action to make the game more immersive

* 5.1 Audio Feedback
  - The game shall provide audio feedback during some special circumstances such as jumping, landing , being killed e.t.c.
    
* 5.2 Haptic Feedback
  - The game shall provide haptic feedback when to compatible devices during special circumstances such as jumping, landing e.t.c.

### User Story User
#### As a Player, I want to be able to play the game with multiple courses inorder to keep me engaged

* 6.1 Menu item
  - The game shall display all the available courses as selectable menu items
    
* 6.2 Multiple Courses
  - The game shall have multiple courses that might differ in theme or difficulty so that the player is engaged in the game for an extended period of time.

### User Story Tester
#### As a Tester, I want to be able to play the game without being "Killed" (i.e game restarting) in any case, so that I can focus on the actual testing of the game instead of being focused on not being killed so that the game does not restart.

* 7.1 No kill mode
  - The game shall have a button that enables No kill mode.
    
* 7.2 No kill mode specifications
  - No kill mode in the game shall allow the player to play the game without being killed.
    
## Adam LaDue
### User Story Developer
#### As a developer, I want to implement a database system that stores player scores and personal records, so that players can track their progress and compare their best performances across different runs with themselves and other players.

* 8.1 The system shall create a new player profile for a new player when the game is first launched
   - 8.1.1 The system shall give a unique ID to the player profile when created
   - 8.1.2 The system shall allow the player to give themselves a username for their profile
   - 8.1.3 The system shall by default give the player a username
   - 8.1.4 The system shall prevent the user from having a username longer than 15 characters long, containing ONLY letters or numbers
   - 8.1.5 The system shall have the player profile contain the personal record of the player

* 8.2 The system shall hold a database containing all player profiles
   - 8.2.1 The system shall have the ability to print all player profiles along with their personal record
   - 8.2.2 The system shall have the ability to print an individual player profile along with their personal record
   - 8.2.3 The system shall have the ability to determine the top 10 scores in the database and print the player profiles associated with them

### User Story User
#### As a player, I want the game to accurately track and save my scores and personal records, so that when I finally beat a record I’ve been striving for, it’s securely stored and my progress is never lost. This will keep me motivated to continue playing and improving without the frustration of losing my achievements.

* 9.1 The system shall correctly keep track of the players score throughout the level
   - 9.1.1 The system shall calculate a proper score per each feat completed (such as, 10 points for a normal jump and 100 points for a difficult jump) and add it to the total score
   - 9.1.2 The system shall update the player's profile personal record upon death, both locally and in the database, if current score is larger than the current personal record

* 9.2 The system shall not allow player profiles to be changed except for the username
   - 9.2.1 The system shall prevent a player from changing their personal records manually
   - 9.2.2 The system shall prevent a player from changing player profile information of other players
   - 9.2.3 The system shall have a back up of the database in case of loss of data

