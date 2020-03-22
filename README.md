# Go-No-Queue-Rush-Estimator-for-Corporate-Cafeteria

In this project you will learn how to build a “people counter” with OpenCV and Python. Using OpenCV, we’ll count the number of people who are heading “in” or “out” of a department store in real-time.

Building a person counter with OpenCV has been one of the most-requested topics here on the PyImageSearch and I’ve been meaning to do a blog post on people counting for a year now — I’m incredibly thrilled to be publishing it and sharing it with you today.

# Required Python libraries for people counting
In order to build our people counting applications, we’ll need a number of different Python libraries, including:

NumPy for python3, $ pip install numpy
OpenCV , pip install opencv-python to install opencv
dlib
imutils


# Project structure
Let’s review the project structure for today’s blog post. Once you’ve grabbed the code from the “Downloads” section, you can inspect the directory structure with the tree  command:

OpenCV People Counter
$ tree --dirsfirst
.
├── pyimagesearch
│   ├── __init__.py
│   ├── centroidtracker.py
│   └── trackableobject.py
├── mobilenet_ssd
│   ├── MobileNetSSD_deploy.caffemodel
│   └── MobileNetSSD_deploy.prototxt
├── videos
│   ├── example_01.mp4 any video
│   └── example_02.mp4
├── output
│   ├── output_01.avi
│   └── output_02.avi
└── pc1.py
4 directories, 10 files
