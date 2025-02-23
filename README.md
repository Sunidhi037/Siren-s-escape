# Siren-s-escape


(A). TEAM MEMBERS AND THEIR RESPECTIVE ROLES:-


1. Amisha --> graphics, music selection, game visuals and audio
2. Sunidhi --> scene 1 (Menu page) unity set-up, coding, git hub, deployment, security testing.
3. Nikita --> scene 2 (Game) unity set up, coding, demo video, scene 2 background image building.

   

(B). INTRODUCTION:-

Siren's Escape is a fast-paced, single-player 2D game built using Unity. The game puts the player in control of a siren who must jump to avoid various obstacles while aiming to survive for as long as possible. The objective is to rack up the highest score by surviving longer with each game attempt.


(C). GAME OVERVIEW:-

1. Game Title: Siren's Escape
2. Platform: Desktop (PC)
3. Engine: Unity
4. Genre: Action/Endless Runner
5. Game Type: Single-player
6. Target Audience: Casual gamers, action fans, anyone looking for a quick challenge


(D). GAMEPLAY DESCRIPTION:- 

In Siren's Escape, the player controls a siren character that continuously moves forward using spacebar. The player must jump over an increasing number of obstacles such as rocks, and underwater debris to survive. The speed of the game and the frequency of obstacles increase as time progresses, making it a progressively difficult challenge to survive.



(E).FEATURES:- 

1. Endless Runner Gameplay:-  The game does not have a set end. The primary goal is to survive as long as possible while avoiding obstacles.
2. Simple Control:
      Jump: Press Spacebar to jump over obstacles.
3. Obstacle Variety: Rocks will appear as the game progresses.
4. Scoring System: Players earn points based on the time they survive.
5. Sound Effects & Music: Atmospheric sounds and music enrich the gameplay experience.
6. High Score Tracking: Keeps track of the highest score achieved during gameplay.


   
(F). TECHNOLOGY STACK:- 
Unity Technologies

--> Game Engine:- Unity (version 6.0.0 used for the project).

--> Programming Language:- C# for scripting.

--> Graphics:- Created using Photoshop and Aseprite for pixel art; Unity’s 2D tools for animation.

--> Audio:- Background music and sound effects are imported into Unity and applied using the AudioSource component.

Other tools used:- 

--> GitHub: Version control and collaborative development.



(G). GAME MECHANICS:- 

Core Gameplay:- 

(a). The game character, the siren, moves forward automatically.

(b). The player must use the spacebar to jump over obstacles (i.e., rocks).

(c). The game speeds up as the player progresses, making it more challenging and difficult to avoid obstacles.

(d). The player earns points based on the duration of survival.

Obstacle:-

Rocks: Static objects that must be jumped over.

Controls:-

Spacebar, to make the siren jump.

Scoring:-

Points are awarded based on the amount of time survived.

A high score is tracked and displayed after each game session.



(H). UNITY IMPLEMENTATION:- 

Scene Setup:-

--> Main Scene:-

  Contains the game objects, including the player(siren), obstacles and the background.

  The camera is set to follow the player's movement while keeping the game area visible.

-->Player Object (Siren):-

  The player is controlled via a Rigidbody2D component, which provides physics-based movement.

  A Collider2D is used to detect collisions with obstacles.


  Obstacles:-

  Obstacles are spawned using an Object Pooling system to avoid instantiating objects repeatedly, which could lead to performance issues.

  Each obstacle is a GameObject with its own Collider2D and is given a script to handle movement and collision detection.


  Game Logic:-

  The GameController script handles game state management, scoring, and timing.

  ScoreManager tracks the player’s survival time and updates the UI.

  ObstacleSpawner is responsible for spawning obstacles at randomized intervals.


  Audio:-

  The AudioSource component is used for playing background music and sound effects (e.g., jumping sound, collision sound, game over sound etc).

  Audio clips are assigned through the Unity Editor.


  UI:-

  Canvas is used to display in-game UI elements such as:-

  1. Score: Displayed at the top of the screen.
  2. Pause: A button to pause the game.
  3. Game Over: A screen that appears when the player dies with the option to restart the game or view the high score.



(I). USER INTERFACE(UI):-

Main Menu:
PLAY : Begins the game session.

HIGH SCORES: Displays the top scores.

QUIT: Quits the game.

In-Game UI:-

Score Display: Located at the top-left of the screen showing the player's current survival time.



(J). DEVELOPMENT PROCESS:- 

Phase 1: Concept and Design-

Brainstormed the core game mechanics: jumping, obstacles, scoring.

Designed the core game loop and user flow.

Created initial sketches of characters and obstacles.


Phase 2: Prototype:-

Developed a basic prototype in Unity with simple jump mechanics and one type of obstacle.

Tested physics interactions, player movement, and obstacle behavior.

Phase 3: Game Development:-

Expanded the prototype by adding obstacles, increasing the speed as the game progresses.

Created graphics for the siren and obstacles.

Developed the scoring system and implemented high score tracking.

Phase 4: Polishing & Testing:- 

Added sound effects and background music for immersive gameplay.

Conducted playtests and refined gameplay mechanics based on feedback.

Optimized performance to ensure smooth gameplay.

Phase 5: Finalization:-

Implemented the main menu, pause functionality, and the game over screen.

Final bug fixes and optimizations for smooth gameplay.

Prepared the game for presentation.


(K). CHALLENGES FACED:-

Balancing Difficulty: It was challenging to scale the difficulty in a way that was engaging but not frustrating.

Performance: Ensuring smooth performance as obstacles increased in number and speed.

Collision Detection: Ensuring precise and responsive collision detection between the player and obstacles.




(L). FUTURE IMPROVEMENTS:-


Power-ups: Add power-ups that could aid the player, such as shields or temporary invincibility.

New Obstacles: Introduce new types of obstacles, such as moving platforms or water currents.

Multiplayer: Add a competitive multiplayer mode where players can race to survive the longest.

Leaderboards: Integrate an online leaderboard to display high scores from all players




CONCLUSION:-


Siren's Escape is a thrilling 2D action game that uses Unity to deliver a fast-paced, engaging experience. The simple controls and challenging mechanics offer players a fun way to test their reflexes and improve their skills. With the current features, there's great potential for expansion, and the game will continue to evolve as new mechanics and challenges are introduced.

















