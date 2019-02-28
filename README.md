# Da-Gam

Development of puzzle/platform game on the Construct 2 engine. The project is designed around a simple yet versatile concept : The 2D environment includes 3 colors only : Black, White, Red. The player can chose to be colored in Black or White. 

- A black element can only interact with an element of the same color, and vice versa.
- A red element can interact with any object of any color at any moment.

The 2D environment is supposed to be a small tricolor archipelago. Each island represents a puzzle.

The player moves with the ZSQD or the arrows keys. He can use the mouse to alternate his colors as he sees fit. The player can also lift and move objects by placing his cursor on them and pressing E or 0.

## Existing modules

At present, the project includes 8 modules considered stable:

- Player movements
- Player/object interactions
- Changing the player's colors
- Dynamic light
- Camera
- Teleporter object
- Moving platforms
- JumpPads

For 3 modules still being working on, but also considered stable :

- Joins between objects (work in progress - stable)
- Sounds (work in progress - stable)
- Kinetic energy management (work in progress - stable)
- Management of color inversion (work in progress - stable)

## In coming Features

- Implementation of several new puzzles
- Various graphic improvements (adding backgrounds being the priority)

## How to play

Get the current build of the project (DaGamBuild) then launch its index.html.

The game can normally be started on localhost, without needing any upload. An error message may indicate that it is recommended to upload the build, but you can ignore it. Now, if you encounter difficulties to launch it this way, try to actually upload the build to an online or local server, via WAMP for example.

The controls are quite simple : 

- Forward : D/Right arrow
- Backward : Q/Left arrow
- Jump : Z/Up arrow
- Changing your current color : Left click
- Interact with any object : Cursor on the object + E/0

On each environment, it is necessary to reach and then activate all the triggers (levers) and then return to the spawn.

## Prerequisites

Chrome, Opera or Firefox browser recommended. Currently not very compatible with Edge or Internet Explorer.

## Used for the Build

*[Construct 2](https://www.scirra.com/construct2) - The game engine used
*[Sprite DLight](http://www.2deegameart.com/) - Normal maps creation tool
*[Spriter](https://brashmonkey.com/) - 2D animation creation tool

## License

This project is under MIT license - see the file[LICENSE.md](LICENSE.md) for more details.


