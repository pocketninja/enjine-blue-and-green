
# Blue and Green

This is a rudimentary example of a tic-tac-toe like game. It demonstrates a very simple game made with Enjine, a toy ECS
JS game engine I'm chipping away at.

It demonstrates a few things:

* Using some of the core Enjine classes (`Game`, `Component`, `System`, etc...)
* Using systems to handle game logic
* Using systems to handle animation
* Using various components to present game visual (renderer components for example)
* Combining reactive HTML (via Alpine.js) with events dispatched from Enjine to create a "HUD" of sorts

NB: The repo for Enjine itself is not publicly available right now - it's very unfinished and lacks many core features. 