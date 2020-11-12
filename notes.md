1. Architecture overview
   ![alt text](https://github.com/Jelly123456/Autonomous-Vehicle-System/blob/main/Images/Capture4.JPG)
   
   Sensing is to extract meaningful information from sensor raw data. Perception is to localize the vehicle and to understand the current environment. Decision is to take actions so as to reliably and safely reach target desitinations.
   
   The three main tasks in autonomous driving perception are localization, object detection, and object tracking.
   
2. Localization
    Localization algorithms aim at calculating the pose (position and orientation) of the autonomous vehicle as it navigates.
    
    Although much progress has been reported in the area of deep learning based localization, VO(Visual Odometry) techniques are still dominated by classical keypoints matching algorithms, combined with acceleration data provided by inertial sensors. This is mainly due to the fact that keypoints detectors are computational efficient and can be easily deployed on embedded devices.
    
3. Path planning and behavior arbitration
    The ability of an autonomous car to find a route between two points, that is, a start position and a desired location, represents path planning.
    
    Two popular deep learning paradigms are imitation learning and deep reinforcement learning.
    DRL(deep reinforcement learning) for path planning deals mainly with learning driving trajectories in a simulator
