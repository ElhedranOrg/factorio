# factorio
Small based city block stuff for Factorio game.  Mostly a place to record thoughts now but may change

## Approach

City blocks, defined by the placement of roboports, aligned to rail such that rail can sit directly next to robo ports.

Blocks can be 1, 1.5, 2 blocks etc, although if covering partial blocks must only do so to connect to rail (which often covers out of block)

For rail, signals are only on incoming side, drive on the right.  This is because unless its clear what is next, it isn't possible to pre-plan which type of signal is needed.

Trains are 1x4, mostly because they fit in a small city block approach and because the game highlights 5 spots total on a station by default.

Train carrage filters will be used.  When creating a block that has a station, the incoming train is pre-created, the outgoing train is not.

No decision yet on whether or not to include a bus.

smelters are not electric.  Also coal is fixed for any block that uses coal to run along side the same edge the rail is on, in the same direction.
