# Object_tracking
Tracking and counting vehicles

# Overview
This project focuses on counting vehicles in a video. At first glance, it might seem that detecting vehicles and simply counting them would suffice. While this approach works for images, it falls short for videos. In videos, the object detection process is repeated for each frame. For example, if a video runs at 30 frames per second, each vehicle would be detected and counted 30 times per second, which is clearly inaccurate. Therefore, besides object detection, a method to track vehicles is needed to ensure each vehicle is counted only once.

