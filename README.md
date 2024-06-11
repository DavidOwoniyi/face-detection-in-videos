This is a simple program that detects faces in videos.

It uses Python and openCV. 
OpenCV is a library that contains pretrained models that can be used for face detection.

The models used is called: Haar cascade classifier for face detection.

The first step is to import the OpenCV library and load the face detection model.
We then gain access to our camera in which we'd be using for video capturing.
We then use the model to detect faces in the video capture and then
draw rectangles on the faces in real time.

The video is worked on frame by frame, so this is how face detection possible.
