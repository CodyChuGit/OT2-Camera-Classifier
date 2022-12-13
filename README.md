# Opentrons-Camera
An exploration of usage potential for the OT-2 onboard camera unit

This program has 5 sub programs/actions:

1. Master image perspective correction -> A source image is taken from a "Master" OT-2 robot. This image serves as a ground truth that future images will reference so all collected data is aligned, regardless of variation in manufacturing camera positioning.
2. image alignment and transform getter -> Extract contrast markers from future images so that collected images are all
3. image segmentation -> 
4. data collection -> 
5. data parsing -> user must manually parse their collected images and place them in >machine_learning to create custom descriminators
6. training and learned model export ->

Follow this install tutorial to setup tensor flow
https://www.tensorflow.org/install

To take images from the OT-2 camera, follow this guide:
https://support.opentrons.com/s/article/Using-the-OT-2-s-camera

This project is based on opensource projects:
https://github.com/nicknochnack/ImageClassification/blob/main/Getting%20Started.ipynb
https://docs.opencv.org/4.x/examples.html
