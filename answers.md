Part 4
Set7
1. act, getActors, processActors, getMoveLocations, selectMoveLocation, makeMove
2. getActors, processActors, getMoveLocations, selectMoveLocation, makeMove
3. Yes. if the new subclass selects its actors from another location other than critter, it needs to override this method
4. getMoveLocations, selectMoveLocation, makeMove
5. Critter extends actor
Set8
1. The act method calls getActors, processActors,getMoveLocations, and selectMoveLolcations
2. The makeMove method first changes the direction of the critter to face its new location.
3. Modify the makeMove method to put flowers in old spots
4. (4,3), (4,4), and (4,5)
5. If the parameter loc in makeMove is equal to the crab critter’s current location, it turns instead of moving. 
6. This method only removes actors
that are not rocks and not critters.

Part 5
1. The isValid method is specified in the Grid interface. The BoundedGrid and UnboundedGrid
classes implement this method. 
2.  It calls getOccupiedAdjacentLocations,
which calls getValidAdjacentLocations which calls isValid. 
3. Method getNeighbors calls the Grid methods
4. the get methor terursn a ref to object in the grid at the location or null if nothing exists.
Set11
1.