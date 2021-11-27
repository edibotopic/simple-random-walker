# Simple Random Walker

This is a simple implementation of a random walk algorithm.

![Cover image](/simple-random-walker.p8.png "Cover image for pico-8 cart")

## Controls

The player is given four options in the main menu that generate different patterns:

- ⬅️ = DIFFUSER
- ➡️ = TILER
- ⬆️ = BUILDER
- ⬇️ = BLOBBER

Making a selection initiates the random walker.
At any point the player can return to the menu by pressing <kbd>Z</kbd>.

## Application

While drawing, the algorithm randomly selects from one of four greyscale colours.

This means that the images generated can be used as simple height maps.

![Example of builder pattern](/builder.gif "Example of builder pattern")

### Instructions

*TODO: add instructions to save images and generate heightmaps*

## Examples

*TODO: examples of generated images and corresponding height maps:*

**3D meshes (will be) generated from heightmaps using Ephtracy's Aerialod**

## Limitations

- No collisions are implemented so that walker can run off the screen (intentional)
- The name of the walker may overlap with generated patterns (intentional)
- Player cannot generate image file from generated patterns (unintentional)
