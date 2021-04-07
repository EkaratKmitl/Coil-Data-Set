
Coil - v2 2021-04-07 10:52am
==============================

This dataset was exported via roboflow.ai on April 7, 2021 at 3:53 AM GMT

It includes 5 images.
Label are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Randomly crop between 0 and 37 percent of the image
* Random shear of between -38° to +38° horizontally and -17° to +17° vertically
* Random brigthness adjustment of between -49 and +49 percent
* Random Gaussian blur of between 0 and 4 pixels


