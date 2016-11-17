# Fog-of-War
Implements the Reddit Challenge of Fog of War using PyGame

#Fog of War

This challenge focuses on implementing different types of "fog-of-war" efects. The provided code is a top-down "game"
 consisting of a player controlled sprite, roving wolves and collidable trees. 
 
Github repo: https://github.com/reddit-pygame/Foggy

Challenge thread: https://www.reddit.com/r/pygame/comments/4u8iht/challenge_fog_of_war/
 
#Challenge 
 
There are three options for this challenge:

**Dark Vision** - The player can only see the portion of the game world within 200 pixels of the player's character.

**Fading Light** - The player can only see the portion of the game world within 200 pixels of the player's character. Additionally,
 the greater the distance from the player the more the world is obscured by darkness (as if the player was using a torch).

**RTS** - Play starts with the game world unexplored. Any portions of the map which the
 player passes within 200px of become permanently discovered. The portion of the world within 200px of the player is visible.
 The unexplored area of the world should be completely obscured. In portions of the map that have been discovered but are not
 visible, only the terrain and trees should be visible. These portions should be darker than the currently visible area. This style of
 fog-of-war is common in RTS games like Age of Empires.

###Controls

*Arrow keys* Move player sprite

*F* Toggle fullscreen

*ESC* Exit
