# Simple Random Walker 🚶 🚶‍♀️ 🐕

This is a simple implementation of a random walk algorithm.

![Cover image](/simple-random-walker.p8.png "Cover image for pico-8 cart")

It is playable on desktop or mobile through the browser via a [web player](https://edibotopic.github.io/simple-random-walker/).

My goal here is primarily academic and relates ultimately to proceduralism in food design, which I am currently writing about.

## Controls

The player is given four options in the main menu that generate different patterns:

- ⬅️ = DIFFUSER
- ➡️ = TILER
- ⬆️ = BUILDER
- ⬇️ = BLOBBER

Making a selection initiates the random walker.
At any point the player can return to the menu by pressing <kbd>Z</kbd> (desktop/laptop) or <kbd>O</kbd> (phone)

## Use-case

This was created as part 1 of a 3-step demo for:

1. Procedural generation of a height map
2. Conversion of a height map to a 3D mesh
3. 3D printing of procedurally-generated structures

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

## To-do

- [ ] Add <kbd>O</kbd> prompt to main menu
- [ ] Dynamic user influence on walkers
- [ ] Instructions on using cart within Pico-8
- [ ] Example 3D models and printed structures
- [ ] Replace grey background around cart
- [x] Change title metadata in index.html
- [ ] Option to recolour pixels during draw
- [ ] Try importing a model to picoCAD
