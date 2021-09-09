# espeleo_gazebo
### *In Development*
Implemented:

- Teleoperation
- Cameras
- Hokuyo
- Imu
- LiDAR
- Camera d465

## Necessary Packages

 ### Velodyne Plugin
    $ cd catkin_ws/src
    $ git clone https://bitbucket.org/DataspeedInc/velodyne_simulator.git
    $ catkin_make or catkin build
    $ source ~/.bashrc


## Initial development package of the EspeleoRobo simulated in the Gazebo

    $ roslaunch espeleo_gazebo spawn.launch

*Robot Model*
![image](https://user-images.githubusercontent.com/51409770/132708822-ecff9ed0-87a5-495e-a4ae-58a8a9d069f0.png)

*Simulation with depth camera and Velodyne*
![image](https://user-images.githubusercontent.com/51409770/132708920-695ead8c-b1b8-498e-a26f-385bcb6dbe9e.png)

*Simulation with laser scan and cameras*
![image](https://user-images.githubusercontent.com/51409770/132574250-28e704bd-c9ff-4377-af3a-2db83e515956.png)

