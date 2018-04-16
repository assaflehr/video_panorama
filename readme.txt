Goal:
Input: a video (moving aerial footage of cars in a highway)

Output:
1. background only video - a video without the moving objects (the cars) 
2. insert objects into the video, to be seen as they are part of it.

How:
see video-panorama.ipynb for implementation (uses opencv).
In high-level , create panorama view of the entire-video (stich frames togeher)
To remove moving-object, use median-blending.
To insert objects project an image into the panorama plane.
In both cases, cut frames from the panorama correspanding to original frames.

