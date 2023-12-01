# Vehicle Detection, Tracking, and Speed Estimation using YOLO-Based Architecture with Road Line Detection and Spatial Analysis

In this project we propose a method to perform vehicle detection and counting that is based on the YOLO architecture while incorporating a Tracker mechanism to track the vehicles' positions as they traverse the road. To detect the road lines, the approach utilizes the Canny edge detector and Hough Line Transform, followed by employing K-means clustering for road line identification. Subsequently, the YOLO architecture is employed to detect vehicles within image or video frames, and the Tracker is utilized to monitor their positions. The counting of vehicles is accomplished by considering their location within predetermined regions of interest on the road. Evaluation of the method using various videos has shown its effectiveness in accurately detecting and counting vehicles.

For speed estimation, the method relies on calculating the distance between two points along a vehicle's trajectory and determining the time taken by the vehicle to travel between those points. The time is derived from the video frame rate, while the distance is computed based on the vehicle's position within the image. Notably, this speed estimation algorithm does not depend on external measurements or stereo vision, yet it delivers a reasonably accurate estimation of a vehicle's speed.


## Files

In this repository, there are 6 files:
- `VCS_report.pdf`: a report in which we summarize the analysis process and the tool developed;
- `VCS_code.ipynb`: colab notebook wrote in python with the spurce code of the tool;
- 4 videos with different roads in different traffic and illumination conditions.
