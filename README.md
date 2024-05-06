==============================QUAKE 2: SPEED MOD==============================

This mod modifies Quake 2 into a speed-focused runner game.  This includes new 
movement mechanics, power-ups, and modifications to player movement and
enemy behavior/stats.

Installation:
1) Download Q2_Speed.zip from Releases, extract it, and move the folder 
(Q2_Speed) to your base folder for Quake 2.
2) Move highscores.txt from Q2_Speed to the base folder for Quake 2.
3) Change "Quake 2 Mod" shortcut's target to: 
"{your game dir}\Q2_Speed\quake2.exe".  DO NOT CHANGE THE COMMANDS 
(i.e. +set game....)

Objective: 
Survive for as long as you can.  Surviving for 10 seconds counts as one full 
lap.  Rack up as many laps as you can!

Controls:
- WASD movement
- Shift (Hold)          : Sprint
- Left Alt              : Crouch
- Space                 : Jump (press again to Double Jump)
- C                     : Levitate 
- F                     : Forward Blink
- F (while crouching)   : Slide
- Q                     : Dodge Left
- E                     : Dodge Right
- 2                     : Equip Superjump Powerup
- 3                     : Equip Noclip Powerup
- Left Click            : Use Equipped Powerup
- F1                    : Help Screen

Changes:
- Movement Abilities:
    - Left/Right Dodges (cooldown)
    - Crouch Slide      (cooldown)
    - Forward Blink     (cooldown)
    - Levitate          (must be grounded first)
    - Double Jump       (after player lands from DJ, player must press Space 
                        again to just ready next Jump attempt)
- Power Ups:
    - Armor         : Temporary Speed Boost
    - Health        : Survive a hit from Berserker
    - Shotgun       : Superjump (uses 1 shell)
    - Super Shotgun : Noclip (uses 2 shells) (limited time of effect)
    - Grenade       : Invincibility
- Berserker:
    - Immune to all damage
    - Will constantly chase player
    - Faster run speed
    - Attacks will oneshot player
- Player Movement:
    - Much faster than base Q2
    - BHopping-type movement (player accelerates much faster)
    - Player health is set to 10
- Stats Tracking:
    - Game keeps track of:
        - timer
        - laps completed
        - current player speed
        - ability cooldowns
        - Noclip/Invincibilty duration
    - Game will save highest lap count and time completed in a txt file
        - will be visible when game is opened again in Help Screen starting
          a new run
