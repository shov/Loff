# Loff
Layers of flats puff world

# Plan

The world consists of the same size objects placed in a grid. Everyone has coords like X,Y. It's about one layer (Z). And there are many layers, so therefore an object has X,Y,Z coods.

The player is like an object but it can move throught the world and look around. It isn't possible for player (object) get a taken place (by another object). The air isn object, it's just free space.

[For now I'm gonna create one player manually and late I'll build Auth system with registration]
So in order to login as player and start observe/move (explore) one has to use login/password. It one hasn't them one has to register to recieve them. 

Every object has a texture as a name->url pair
We can get information about existing layers
We do not draw layers over the player
We draw all layers under the player
Player can fall down if under one there no objects to collide: gravity [For now I'm going to set gravity=false]
If player fall down one will die 💀

