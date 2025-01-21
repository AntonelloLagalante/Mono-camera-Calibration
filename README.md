# Mono-camera-Calibration

Scripts able to compute the Intrinsics (K) and Extrinsics ([R|t)] of a Mono-Camera, given:
- Set of images of with chessboard on the scene
- A single image containing 4 markers with know real-world coordinates

The reference system convention for the camera is the one used in the OpenCV library and reported in the follow:

![alt text](https://docs.opencv.org/3.4.0/pinhole_camera_model.png)
