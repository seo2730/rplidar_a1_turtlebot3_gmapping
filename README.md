# rplidar_a1_turtlebot3_gmapping
Using rplidar a1 instead of  LDS-01

# Install rplidar driver
git clone https://github.com/robopeak/rplidar_ros<br>

# Install launch files
turtlebot3_rplidar.launch put in<br><br>

    mv turtlebot3_rplidar.launch /[ros_workspace]/src/turtlebot3/turtlebot3_bringup/launch/turtlebot3_rplidar.launch<br><br>

turtlebot3_gmapping.launch pun in <br><br>

    mv -f turtlebot3_gmapping.launch /[ros_workspace]/src/turtlebot3/turtlebot3_slam/launch/turtlebot3_gmapping.launch






