# SFML RPG

**11/4/17 -**

    Projectiles Added.
    
    Errors:
      - Need to take projectiles out of main loop
      - When return rect.getPosition, says its a vector2f not a float. (Conversion error).
      - Projectiles need to be set to the players position
      - Set setters/getters for needed variables (lol rip).
      - Projectiles non-stop spawning (see space bar, maybe error?).
      
**11/6/17 -**

    Fixed errors:
      - Projectiles out of main loop
      - Fixed conversion error with rect.getPosition
      - Projectiles spawn on main player
      - Projectiles don't non-stop spawn anymore.
      
    Current changes needed:
      - Create world class
      - Create game class
      - Change entity class so its more in depth. (lots of recurring code between enemies/other characters)
  
