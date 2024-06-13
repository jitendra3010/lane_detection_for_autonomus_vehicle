# lane_detection_for_autonomus_vehicle
Lane Detection Using Segmentation/Equalization/Edge Detection/Filtering

An Image Analysis Technique for Lane detection is proposed here. The system exploits the characteristics of the gray level histogram of the road to detect lane markers. Each lane marker is then analyzed on a region of interest with edge detection(Canny) filtering technique and masking. Finally, the lane markers are highlighted in green with a riding pane to create structures defining the lane boundaries.

<img width="464" alt="image" src="https://github.com/jitendra3010/lane_detection_for_autonomus_vehicle/assets/53829596/9fa3da79-8bef-432b-a4d8-6a3ce575e9e2">


Conclusion
In the ideal road scenario, the algorithm performed very well in straight line segments, and in some parts of smooth curves (conditions ideally found on a highway), it detected lanes. In contrast, the lanes are almost perpendicular to the camera on the dashboard. We also tested the algorithm on Chicago roads, where we saw some problems while passing through under a bridge and changes in light conditions and the color of the road. (Sample video output shown in the presentation with the issues). Overall, the algorithm performed well and did a decent job of identifying the lanes on the road and eliminating other objects from other lanes.

 
Future work
The short-term goal with this algorithm is to apply the below techniques and see how the algorithm performs.
 
• Different segmentation methods to ignore the color condition of the road.
• Possible contouring to fill colors for lanes only. <Suggestion>
• Decision Tree classification techniques to group curves and identify angles for detecting curves better.
• Better thresholding technique to detect different color markings for better results.
• Exploring Hough Lane detection technique for better results.
• Also implementing Bayesian parameter estimation to merge the results of previous frames with the current frame, which will produce a more stable and reliable result, especially for dashed lines.


References
[1] 2000 IEEE Intelligent Transportation Systems Conference Proceedings Dearborn(MI),USA0 Octoberl-3,2000
[2] Kluge, K. and Lakshmanan, S. “A Deformable- Template Approach to Lane Detection”. Proceedings Kluge, K. and Lakshmanan, S. “A Deformable- Template Approach to Lane Detection”. Proceedings
[3] Bertozzi, M. and Broggi, A. “GOLD: a Parallel Real- Time Stereo Vision System for Generic Obstacle and Lane Detection”, IEEE Transactions on Image Processing, Vol7, No. 1, January 1998,62-81.
[4] Bertozzi, M. and Broggi, A. “GOLD: a Parallel Real- Time Stereo Vision System for Generic Obstacle and Lane Detection”, IEEE Transactions on Image Processing, Vol7, No. 1, January 1998,62-81.
[5] Bertozzi, M. and Broggi, A. “GOLD: a Parallel Real- Time Stereo Vision System for Generic Obstacle and Lane Detection”, IEEE Transactions on Image Processing, Vol7, No. 1, January 1998,62-81.
