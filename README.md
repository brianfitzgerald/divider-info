# Divider for Blender

If you're reading this, I'm assuming you've purchased Divider for Blender. Thank you! Below is an explanation of its features and options, and some answers to common questions.

## How to Use

* Click 'create plane'.
* Fiddle with parameters.
* Click 'Subdivide'.
* Enjoy!

## Options

* Num Subdivs - How many times the selected mesh is subdivided. Larger numbers might cause slowdown or crashes; usually 3-5 is a good range.
* Offset - This is the amount of offset that each subdivided division is moved by after it's divided. This is the main 'knob' for changing the end result's look.
* Animation End Offset - pretty explanatory, this is what the value of offset will be at the end of the animation sequence, i.e. the last keyframe.
* Keyframe Interval - how many frames between each keyframe.
* Num Keyframes - The amount of keyframes to interpolate between. Usually a division of 5 works best.
* Noise Amount - Applies random noise to each subdivision, which can add a more 'natural' feel.
* Extrude Style - Flat applies no extrusion, Hilly only extrudes every few faces, and even / odd extrudes the opposite set of faces between each keyframe.
* Use Normal Direction - Good for non-plane meshes

## FAQ

### Can I use non-planes?

Yes, although the effect was built for planes, and you might get weird results, though some (especially spheres) work well.

### Can I subdivide the same plane twice?

No.

### I found a bug.

Create an issue on this repo, and I'll look at it.

### I have an idea / something I want to do that's not supported

Send me proof of purchase, and I'll send you the source code if you want to implement it yourself; otherwise, add a Suggestion issue here.
