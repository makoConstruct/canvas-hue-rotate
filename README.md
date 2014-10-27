A function for performing hue rotations on a canvas. Uses a single matrix multiplication per pixel. Not sure if that's a genuine hue rotation, the math doesn't feel right, but it looks pretty good, and it's a relatively fast way of doing things.

Note, if you're not supporting IE, you probably want to use css filters.