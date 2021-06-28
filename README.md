# Quadcopter-UAES
**Unmanned  Aerial Exploration System**

Self-flying, which we might call self-piloting, is the ability of a drone to perform aerial maneuvers without a human at the controls. This technology is being used in many domains nowadays – weather forecasting, fire departments, infrastructural managers, wildlife photography and in farming too.
For implementing this approach we use ROS in which we are using mapping and localisation , In this we are using mapping in which the drone moves around with mapping and sees is any object is there . After that it uses localization to identify the position of the drone and after the path planning it shows the path and navigate the drone to move on the path. We are getting the results by using mapping and localisation and our drone is also working properly.

## Installation

Use the below mentioned links for proper setup.

Linux <https://releases.ubuntu.com/16.04/>

Ros Kinetic <http://wiki.ros.org/kinetic/Installation/Ubuntu>

Packages <https://www.theconstructsim.com/how-to-launch-drone-simulation-locally>
## Usage
After installation 
```python
roscore (terminal 1)

source ~/parrot_ws/devel/setup.bash (terminal 2)

roslaunch drone_construct main.launch (terminal 2)

source ~/parrot_ws/devel/setup.bash (terminal 3)

roslaunch gazebo_ros empty_world.launch (terminal 3)
```

## Output
(https://github.com/Frankenstein-byte/Quadcopter-UAES/blob/main/Pictures/1.png)
## Future work
1. One of the major thing to do in our project will be to implement localisation and mapping for 3D navigation for proper object detection and movement in real time environments.  
2. Fitting our drone with different sensors and digital imaging capabilities is not going to be easy and it would be another important task to do. 
3. Making use of Artificial Intelligence & Machine Learning algorithms can also make the drone much much autonomous and thus it would increase the precision of obstacle detection and avoidance and therefore would make the drone to perform nearly perfect in real life situations where a small mistake can lead to loss of human lives such as delivery of medical necessities on time.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
