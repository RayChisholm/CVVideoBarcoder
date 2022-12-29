# CVVideoBarcoder
This utilizes OpenCV's C++ library to take a video input and produces a barcode image output.

We find the average pixel value for each frame of a video file and create a vertical line with that color. The next frame will be added to the right.

Some examples of output can be found below:

Samurai Champloo Intro:
![champloo_intro mp4](https://user-images.githubusercontent.com/6054047/209894497-1ea98574-b79f-49e6-94b8-7be4da118d06.jpg)

Elden Ring Intro:
![elden_ring mp4](https://user-images.githubusercontent.com/6054047/209894516-3ad6235b-a81f-4af4-b4cf-e3a9e5187091.jpg)
