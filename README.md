# Object_Detection
Recognition of Product Positions on Shelf Images with Deep Learning in Keras / Tensorflow / Object Detection API


Introduction

What is a planogram?

Visual description of the retail products' placement on shelves.
The solution is based on Toward Retail Product Recognition on Grocery Shelves. Back in 2014 they have collected 345 tobacco shelves images from ~40 locations with 4 cameras and have made them available for downloading.  They also cropped over 13,000 products and grouped some of them into 10 brand classes.

Few years ago a planogram reconstruction from shelves photos was not an easy task in both products detection and brands recognition. The work proposes the following combination of algorithms.  It was hard to implement, hard to maintain, hard to expand to include new brands and products.

Recently Convolutional Neural Networks (CNN) have made a revolution in Computer Vision and have changed the way of thinking of such tasks. In the past couple of years, these technologies have started to became available to the broader software development community. User-friendly API such as Keras significantly decreased the barriers to entry. Now days nearly any software developer can in few days start to benefit from the power of Convolutional Neural Networks!

This work shows the power of these cutting edge techniques. It will show that all algorithms proposed above could be easily replaced by only 2 CNNs with increase of recognition quality without losing performance.
