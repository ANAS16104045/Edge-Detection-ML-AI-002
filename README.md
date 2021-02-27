# Edge-Detection-ML-AI-002


@Hewlett Packard empowered Kyrion Technologies, New Delhi. May-June 2018

Edge Detection is an image processing technique for finding the boundaries of objects within images. It works by detecting discontinuities in brightness. Edge detection is used for image segmentation and data extraction in areas such as image processing, computer vision, and machine vision.

Edge Detection includes a variety of mathematical methods that aim at identifying points in a digital image at which the image brightness changes sharply or, more formally, has discontinuities. The points at which image brightness changes sharply are typically organized into a set of curved line segments termed edges. The same problem of finding discontinuities in one-dimensional signals is known as step detection and the problem of finding signal discontinuities over time is known as change detection. Edge detection is a fundamental tool in image processing, machine vision and computer vision particularly in the areas of feature detection and feature extraction


Edge detection algorithms include:- 

• Sobel 

• Canny 

• Prewitt 

• Roberts 

• Fuzzy logic methods.

Applications of Edge Detection

The present and near future main application areas of ED are robotics vision (e.g. in self-driving vehicles) and classification of medical images (to find fingerprints for “diseases” such as tumors).

Identifying objects immersed in images is the main application of edge detection.

Regarding a concrete area of application, it seems to me that the current and (next) future big application of ED is self-driving vehicles (cars, boats, planes, all kind of robots, etc…).

In self driving cars you have tough edge detection problems because the algorithms must perform detection in real time at driving speed: in this case you filter the image for edge detection with some kind of high-pass filters (Laplacian filters are popular for edge-detection) and then some probabilistic or/and AI classification algorithm shall identify which edges in the images correspond to road limits, road separators, roundabouts, nearby vehicles, etc. Other kind of sensing, besides image processing, is used, even if it is to get redundant information, such as radars (see the top of the google SDC below).

Another important area being developed which of course involves edge detection is finding “pathological” objects in medical images such as tumors. Besides ED this involves recognizing textures, etc…
