# SLAM : Implementing SLAM (Simultaneous Localization and Mapping) for Landmark Detection and Robot Tracking. 

This project implements SLAM (Simultaneous Localization and Mapping) for a 2 dimensional world! here I combine what is known about robot sensor measurements and movement to create a map of an environment from only sensor and motion data gathered by a robot, over time. SLAM gives you a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems.

# Model Output

Below is the output of the model, an 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using only sensor and motion data collected by that robot. This is just one example for a 50x50 grid world; in your work you will likely generate a variety of these maps.

![](images/output)

The estimated landmark is near to the true landmark at maximum distance of 2 units. Please find below the approciate values achieved:
true final pose (x=21.34746, y=36.55557) estimate final pose (x=22.76562, y=37.40007)

# To use
Clone the repository using command: git clone https://github.com/PreetiSajjan/SLAM.git

The dataset used is included in the repository so need not to be downloaded explicitly.

# Contribution and References

Feel free to contribute to the project.
Please note that this project was done as part of my course "A Nanodegree in Computer Vision"
** Kindly cite if any part of the code is referred. **
