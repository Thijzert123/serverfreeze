<p align="center">
  <img width="200" height="200" src="https://raw.githubusercontent.com/Thijzert123/serverfreeze/refs/heads/main/serverfreeze/pack.png">
</p>

# ServerFreeze
ServerFreeze is a Minecraft data pack that pauses the game when no players are online. This is to save resources without shutting down the server or to preserve the game time (day/night cycle will pause when nobody is online).

It does nothing if you install it on a singleplayer world.

## How does it work?
- Every tick, Minecraft checks if any players are online.
- If not, `tick freeze` will be executed, which pauses the game.
- The game still checks if players are joining the world;
- If someone connects to the server, `tick unfreeze` will be executed, which resumes the game.
