# css android

The purpose of this project is to re-create the Android logo using CSS and HTML only.
Several versions are proposed.

1. The first version uses `div` and `span` blocks to recreate the shape. It it kind of a quick and dirty test.

1. The second attempt uses a grid to position the blocks. This reduces the need for spacing blocks. Grid cells are of different shapes/dimensions.

1. The third attempt uses a grid made of squares to draw the droid. This makes the logo more easily scalable, as `div`s do not need dimensions anymore. Moreover, each element of the logo is now independent of the others. Note that this solution leads to some approximation, though – e.g., the top of the head of the droid is now flat, due to `grid-gap`.
