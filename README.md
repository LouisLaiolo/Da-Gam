# Da-Gam

Development of a platform reflection game on the Construct 2 engine. The project is based on established, albeit rudimentary, foundations. The 2D environment includes 3 colors: Black, White, Red. The player can be colored in Black or White. 

- A black element can only interact with an element of the same color, and vice versa.
- A red element can interact with any object of any color.

The 2D environment is supposed to be a small tricolor archipelago. Each island represents a puzzle.

The player moves with the ZSQD keys. He can use the mouse to alternate his colors as he sees fit. The player can also lift and move objects by placing his cursor on them and pressing E.

## Existing modules

At present, the project includes 8 modules considered stable:

- Player movements
- Player/object interactions
- Changing the player's colors
- Dynamic light
- Camera
- Management of the teleporter object
- Management of moving platforms
- JumpPad Management

For 3 modules under construction, also stable:

- Management of joins between objects (under work - stable)
- Sounds (under construction - stable)
- Kinetic energy management (under construction - stable)
- Management of color inversion (under construction - stable)

## Features to add

- Implementation of one or more new puzzles
- Various graphic improvements (in particular, adding backgrounds)

## How to play

Get the build of the project (DaGamBuild) then launch its index.html.

The game can normally be started locally, without uploading. An error message will indicate that it is recommended to use an upload, you can ignore it. If it is not possible to launch it as it is, upload the build to an online or local server, via WAMP for example.

The controls are quite simple: 

- Advance: D
- Backward: Q
- Skip: Z
- Colour the player in black: Left click
- Colour the player in white: Right click
- Interact with an object: Cursor on the object + E

On each environment, it is necessary to reach and then activate all the triggers (levers) and then return to the input.

## Prerequisites

Chrome or Firefox browser recommended. Currently not very compatible with Edge or Internet Explorer.

## Used for the Build

* [Construct 2](https://www.scirra.com/construct2) - The game engine used
*[Sprite DLight](http://www.2deegameart.com/) - Normal maps creation tool
*[Spriter](https://brashmonkey.com/) - 2D animation creation tool

## License

This project is under MIT license - see the file[LICENSE.md](LICENSE.md) for more details.


