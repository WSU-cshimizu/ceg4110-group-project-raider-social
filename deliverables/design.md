# Design Specification

### 1.1 & 1.2 Menu Options
![Main Menu](../assets/Main-Menu.jpeg)

- The above picture shows the Main Menu of our game. The game can have multiple options such as Main Lobby, Audio settings, Haptic settings e.t.c. We can add other options to the Main menu if we deem it necessary. 

### 2.1 and 2.2 Matchmaking System
![Leaderboard](../assets/Leader_board.jpeg)

- The above picture is that of a Leaderboard. The highest scores of the payers are stored in a persistant databse, and then showed in the leaderboard in order foster a competitive spirit amongst the players.
### 3.1 & 3.2 Collision Detection
![Screenshot 2024-10-18 115840](https://github.com/user-attachments/assets/7d2233e2-b6bf-4422-9c1e-03c5593c49aa)

- This is the flow chart for how collision detection will be handled. The system will wait for a player input then once an input is detected it will then check if the player hit box is colliding with a wall or the platform hit boxes and will react accordingly.
### 4.1 Game Controls
![Screenshot 2024-10-18 122449](https://github.com/user-attachments/assets/09d88668-67bb-40f1-abd9-60e6b57005c5)

- This is a flow chart for how the player movement will be handled. The system will wait for a input from the player and an input is detected it will respond accordingly depending on where the player is positioned in the game space. This will allow for fluid in-game controls.
### 5.1 Audio Feedback
![Audio Feedback](../assets/Audio-Feedback.jpeg)

- This is the flow chart for Audio Feedback. Whenever a user initiated action occures in the game, various conditions are checked to decide whether a Audio Feedback needs to be generated or not, after which haptic feedback is generated accrodingly.
### 5.2 Haptic Feedback
![Haptic Feedback](../assets/Haptic-Feedback.jpeg)

- This is the flow chart for Haptic Feedback. Whenever a user initiated action occures in the game, various conditions are checked to decide whether a Haptic Feedback needs to be generated or not, after which haptic feedback is generated accrodingly.
### 6.1 & 6.2 Multiple Courses
![Main Lobby](../assets/Main-Lobby-Mockup.jpeg)
- Above is a 2D and 3D diagram of the Main Lobby. From the Main Lobby we can decide to go into one of many courses that might differ amongst themselves interms of theme, difficulty, course structure. 

### 7.1 & 7.2 No Kill mode
![No Kill Mode](../assets/No-Kill-mode.jpeg)

- This is the flow chart for No kill mode. Whenever the user plays the game in No kill mode, the user is respawned immediately after they fall off the platfrom. This feature is usefull in when the tester wants to test a patricular obstacle that is hard to complete. The tester can enable no kill mode and then test the obastacle as many times as they want without having to play the whole game again to reach the difficult section again.

### 8.1, 8.2, 9.1, 9.2 Player Data
![Player Profile](../assets/Player-Profile-Flowchart.png)

- This is the flow chart for the player profile if the user is a new player or not. This flow chart also shows how the player profile is used during gameplay and how it plays a role in the settings from the main menu. 
### 10.1 & 10.2 Frontend Mock-ups
![Course Assets](../assets/Course-Assets-Mockup.jpeg)
![Main Lobby](../assets/Main-Lobby-Mockup.jpeg)

- These are bare-bones mockups of what we expect the basic platforms and obstacles to look like. Most obstacles will likely be a combination of various assets. There is also a mockup of what we expect the main lobby to look like. The player will be able to select from 4 courses in a central "hub"-like room and can proceed into any of the courses to begin.
### 11.1 Physics Based Movement
![Physics Based Movement](../assets/Physics-Based-Movement-Diagram.jpeg)

- The primary physics element the we would like to implemenet (apart from typical elements such as gravity) will be momentum. This will primarily be the mechanic that when a player jumps while running, they will go 2x farther than they would otherwise. This would be based on a particular combination of key presses. If the player is moving forward and jumps while moving, momentup mechanics will apply. If the player is stationary and jumps, they will just jump straight up. If the player jumps then moves forward, they will move forward the default jump distance.
### 11.2 Skill Progression
![Progression](../assets/Skill%20Progression-Diagram.jpeg)

- As the player progresses through a course, it will require more skill to get through obstacles. Earlier stages of the courses will have easier obstacles and they will get more challeneging as the player progresses. Above are some of the easy, medium, and difficult obstacles that will be implemented.
