### SFM and MVS
#### SFM
- feature extract
- feature matching: find the closest correspondence
- refine match: apply RANSAC method to find correspondence which supplies distance constriants
- eight-points method: find eight points to best fit the transformation
- points depth approximation: solve the linear equations to approximate the depth
- draw points

#### MVS
- get epipolar point
- for each pixel, get the corresponding dst pixel
- get the epipolar line
- find the best macthing on the epipolar line
- draw points